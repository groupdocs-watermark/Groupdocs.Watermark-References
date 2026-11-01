---
title: "Documentvoorbeeld"
linkTitle: "Document preview"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Genereer voorbeeldafbeeldingen (PNG/JPG/BMP) voor documentpagina's met GroupDocs.Watermark voor Python via .NET."
type: docs
url: /nl/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark kan documentpagina's renderen als afbeeldingen zodat je paginathumbnails kunt tonen zonder een document volledig te openen in een viewer. Je stuurt de rendering aan met een `create_page_stream` callback die een beschrijfbare bestandsstroom levert voor elke pagina — de bibliotheek schrijft de pagina-afbeelding erin en sluit deze voor je.

## Generate a document preview

Stel [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) in met een `create_page_stream` callback, kies het `preview_format` en geef de `page_numbers` op die gerenderd moeten worden.

{{< tabs \"code-example-preview\">}}
{{< tab \"generate_preview.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Voorzie een schrijfbare bestandsstroom voor elke te renderen pagina.
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` is het twee-pagina's voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab \"generate-preview-outputs.zip\" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

De pagina-afbeeldingen worden naar de huidige map geschreven — één PNG per aangevraagde pagina. Gebruik `PreviewFormats.JPEG` of `PreviewFormats.BMP` voor andere formaten, en stel `options.width` / `options.height` in om de gerenderde grootte te bepalen.

De bibliotheek sluit elk bestand dat `create_page_stream` retourneert zodra de pagina is geschreven. Om op een pagina te reageren zodra deze klaar is, geef je een tweede callback door: `PreviewOptions(create_page_stream, release_page_stream)` roept `release_page_stream(page_number, stream)` aan met het object dat `create_page_stream` voor die pagina heeft geretourneerd, nadat de volledige afbeelding erin staat. Een één-argument `release_page_stream(page_number)` werkt ook. `create_page_stream` kan ook een `io.BytesIO` retourneren: deze blijft open en houdt de pagina-afbeelding vast tot het moment dat `release_page_stream` deze ontvangt.

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
