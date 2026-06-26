---
title: Adding image watermarks
linkTitle: "Adding image"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Add image watermarks from a file or a stream using GroupDocs.Watermark for Python via .NET."
type: docs
url: /python-net/guides/adding-image-watermarks/
is_root: false
weight: 150
---


GroupDocs.Watermark supports adding the following image formats as watermarks:

- BMP
- PNG
- GIF
- JPEG

## Add an image watermark from a local file

The following example adds an [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) to a document. If the document consists of multiple parts (pages, worksheets, slides, frames, etc.), the watermark is added to each of them.

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark, SizingType
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        with ImageWatermark("./logo.png") as watermark:
            watermark.horizontal_alignment = HorizontalAlignment.CENTER
            watermark.vertical_alignment = VerticalAlignment.CENTER
            watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS
            watermark.scale_factor = 0.5
            watermark.opacity = 0.7
            watermarker.add(watermark)
        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_image_watermark()
```

  

`sample.docx` and `logo.png` are the sample files used in this example. Download [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/adding-image-watermarks/sample.docx) and [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/adding-image-watermarks/logo.png).

  
```text
Binary file (DOCX, 125 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/adding-image-watermarks/add_image_watermark/output.docx)

## Add an image watermark from a stream

You can also initialize an [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) from a stream — pass it as the `stream` argument.

  
```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

def add_image_watermark_from_stream():
    with open("./logo.png", "rb") as f:
        data = f.read()

    with Watermarker("./sample.docx") as watermarker:
        with ImageWatermark(stream=io.BytesIO(data)) as watermark:
            watermarker.add(watermark)
        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_image_watermark_from_stream()
```

  

`sample.docx` and `logo.png` are the sample files used in this example. Download [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/adding-image-watermarks/sample.docx) and [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/adding-image-watermarks/logo.png).

  
```text
Binary file (DOCX, 120 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/adding-image-watermarks/add_image_watermark_from_stream/output.docx)

For advanced watermark properties (tiling, alignment, sizing, rotation, and margins), the same techniques shown for text watermarks apply to image watermarks. See [Adding text watermarks]().
