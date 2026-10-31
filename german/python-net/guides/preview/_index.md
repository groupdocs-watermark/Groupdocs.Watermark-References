---
title: "Dokumentvorschau"
linkTitle: "Document preview"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Vorschau‑Bilder (PNG/JPG/BMP) für Dokumentseiten mit GroupDocs.Watermark für Python über .NET erzeugen."
type: docs
url: /de/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark kann Dokumentseiten als Bilder rendern, sodass Sie Seiten‑Thumbnails anzeigen können, ohne das Dokument vollständig in einem Viewer zu öffnen. Der Render‑Vorgang wird über einen `create_page_stream`‑Callback gesteuert, der für jede Seite einen beschreibbaren Dateistream bereitstellt – die Bibliothek schreibt das Seitenbild hinein und schließt den Stream für Sie.

## Generate a document preview

Setzen Sie [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) mit einem `create_page_stream`‑Callback, wählen Sie das `preview_format` und geben Sie die zu rendernden `page_numbers` an.

{{< tabs "code-example-preview">}}
{{< tab "generate_preview.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Stellen Sie für jede zu rendernde Seite einen beschreibbaren Dateistream bereit
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

`sample.pdf` ist die zweiseitige Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf), um sie herunterzuladen.

{{< /tab >}}
{{< tab "generate-preview-outputs.zip" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Die Seitenbilder werden in das aktuelle Verzeichnis geschrieben – ein PNG pro angeforderter Seite. Verwenden Sie `PreviewFormats.JPEG` oder `PreviewFormats.BMP` für andere Formate und setzen Sie `options.width` / `options.height`, um die gerenderte Größe zu steuern.

Die Bibliothek schließt jede von `create_page_stream` zurückgegebene Datei, sobald die Seite geschrieben ist. Um sofort nach Fertigstellung einer Seite zu handeln, übergeben Sie einen zweiten Callback: `PreviewOptions(create_page_stream, release_page_stream)` ruft `release_page_stream(page_number, stream)` mit dem von `create_page_stream` für diese Seite zurückgegebenen Objekt auf, nachdem das gesamte Bild darin ist. Ein ein‑Argument‑Callback `release_page_stream(page_number)` funktioniert ebenfalls. `create_page_stream` kann auch ein `io.BytesIO` zurückgeben: es bleibt geöffnet und hält das Seitenbild, bis `release_page_stream` es erhält.

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
