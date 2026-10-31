---
title: "Anteprima del documento"
linkTitle: "Document preview"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Genera immagini di anteprima (PNG/JPG/BMP) per le pagine del documento usando GroupDocs.Watermark per Python tramite .NET."
type: docs
url: /it/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark può renderizzare le pagine dei documenti come immagini così puoi mostrare le miniature delle pagine senza aprire completamente un documento in un visualizzatore. Il rendering è controllato da una callback `create_page_stream` che fornisce uno stream di file scrivibile per ogni pagina — la libreria scrive l'immagine della pagina su di esso e lo chiude per te.

## Generate a document preview

Imposta [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) con una callback `create_page_stream`, scegli il `preview_format` e elenca i `page_numbers` da renderizzare.

{{< tabs \"code-example-preview\">}}
{{< tab \"generate_preview.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Fornisci un flusso di file scrivibile per ogni pagina da renderizzare
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

`sample.pdf` è il file di esempio a due pagine usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"generate-preview-outputs.zip\" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Le immagini delle pagine vengono scritte nella directory corrente — un PNG per ogni pagina richiesta. Usa `PreviewFormats.JPEG` o `PreviewFormats.BMP` per altri formati, e imposta `options.width` / `options.height` per controllare le dimensioni renderizzate.

La libreria chiude ogni file restituito da `create_page_stream` una volta che la pagina è stata scritta. Per agire su una pagina non appena è pronta, passa una seconda callback: `PreviewOptions(create_page_stream, release_page_stream)` chiama `release_page_stream(page_number, stream)` con l'oggetto `create_page_stream` restituito per quella pagina, dopo che l'intera immagine è presente. Una `release_page_stream(page_number)` a un argomento funziona altrettanto. `create_page_stream` può anche restituire un `io.BytesIO`: rimane aperto e trattiene l'immagine della pagina fino a quando `release_page_stream` la riceve.

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
