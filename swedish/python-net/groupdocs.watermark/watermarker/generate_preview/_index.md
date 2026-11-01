---
title: "generate_preview metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Genererar förhandsgranskningsbilder för dokumentet."
type: docs
url: /sv/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

Genererar förhandsgranskningsbilder för dokumentet.

```python
def generate_preview(self, preview_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Ytterligare alternativ att använda när förhandsgranskningsbilder genereras. |

### Exempel

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

### Se även
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
