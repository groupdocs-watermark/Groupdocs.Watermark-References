---
title: Add image watermarks
linkTitle: "Add image watermarks"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "This article shows how to add an image watermark to a document and save the result with GroupDocs.Watermark for Python via .NET."
type: docs
url: /python-net/guides/add-image/
is_root: false
weight: 50
---


One of the main features of GroupDocs.Watermark is adding image watermarks to documents. You can add watermarks to documents or images from a local path, as well as from a stream. For a full list of supported formats, check [Supported document formats]().

## Add an image watermark

To add an image watermark, follow these steps:

1. Open the document by passing its path (or a stream) to the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) class.
2. Create an [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) from the watermark image file (or a stream).
3. Position the watermark — for example, set `horizontal_alignment`, `vertical_alignment`, and `opacity`.
4. Call `add()` to apply the watermark and `save()` to write the result.

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # Build an image watermark from a logo file and center it
        watermark = ImageWatermark("./logo.png")
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.opacity = 0.7

        watermarker.add(watermark)
        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_image_watermark()
```

  

`sample.docx` and `logo.png` are the sample files used in this example. Download [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) and [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png).

  
```text
Binary file (DOCX, 125 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)

## What's next

GroupDocs.Watermark offers more capabilities for image watermarks — loading from streams, scaling, tiling, and absolute or relative positioning. See [Adding image watermarks]() in the advanced guide.
