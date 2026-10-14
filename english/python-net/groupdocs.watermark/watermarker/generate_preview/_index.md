---
title: generate_preview method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Generates preview images for the document."
type: docs
url: /python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

Generates preview images for the document.

```python
def generate_preview(self, preview_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Additional options to use when generating preview images. |

### Example

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.options import PreviewOptions, PreviewFormats

    def generate_preview():
        # Supply a writable file stream for each page to render
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

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
