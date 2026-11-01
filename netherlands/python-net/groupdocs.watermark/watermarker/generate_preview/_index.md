---
title: "generate_preview-methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Genereert voorbeeldafbeeldingen voor het document."
type: docs
url: /nl/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

Genereert voorbeeldafbeeldingen voor het document.

```python
def generate_preview(self, preview_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Aanvullende opties om te gebruiken bij het genereren van voorbeeldafbeeldingen. |

### Voorbeeld

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

### Zie ook
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
