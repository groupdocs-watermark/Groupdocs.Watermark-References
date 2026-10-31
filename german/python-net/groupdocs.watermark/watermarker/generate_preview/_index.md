---
title: "Methode generate_preview"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Erstellt Vorschaubilder für das Dokument."
type: docs
url: /de/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

Erstellt Vorschaubilder für das Dokument.

```python
def generate_preview(self, preview_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Zusätzliche Optionen, die beim Erzeugen von Vorschaubildern verwendet werden können. |

### Beispiel

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

### Siehe auch
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
