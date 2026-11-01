---
title: "Dokumentförhandsgranskning"
linkTitle: "Document preview"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Generera förhandsgranskningsbilder (PNG/JPG/BMP) för dokumentsidor med GroupDocs.Watermark för Python via .NET."
type: docs
url: /sv/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark kan rendera dokumentsidor som bilder så att du kan visa sidominiatyrer utan att helt öppna ett dokument i en visare. Du styr renderingen med ett `create_page_stream`-återanrop som tillhandahåller ett skrivbart fil-ström för varje sida — biblioteket skriver sidans bild till den och stänger den åt dig.

## Generate a document preview

Ställ in [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) med ett `create_page_stream`-återanrop, välj `preview_format` och lista `page_numbers` som ska renderas.

{{< tabs "code-example-preview">}}
{{< tab \"generate_preview.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Tillhandahåll ett skrivbart filflöde för varje sida som ska renderas
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

`sample.pdf` är den tvåsidiga exempelfilen som används i detta exempel. Klicka på [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab \"generate-preview-outputs.zip\" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Sidbilderna skrivs till den aktuella katalogen — en PNG per begärd sida. Använd `PreviewFormats.JPEG` eller `PreviewFormats.BMP` för andra format, och sätt `options.width` / `options.height` för att kontrollera den renderade storleken.

Biblioteket stänger varje fil som `create_page_stream` returnerar när sidan har skrivits. För att agera på en sida så snart den är klar, skicka en andra återanropning: `PreviewOptions(create_page_stream, release_page_stream)` anropar `release_page_stream(page_number, stream)` med objektet `create_page_stream` som returnerats för den sidan, efter att hela bilden är i den. En en‑argument `release_page_stream(page_number)` fungerar också. `create_page_stream` kan också returnera en `io.BytesIO`: den förblir öppen och behåller sidans bild tills `release_page_stream` får den.

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
