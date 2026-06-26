---
title: Add text watermarks
linkTitle: "Add text watermarks"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "This article shows how to add a text watermark to a document and save the result with GroupDocs.Watermark for Python via .NET."
type: docs
url: /python-net/guides/add-text/
is_root: false
weight: 10
---


One of the main features of GroupDocs.Watermark is adding text watermarks to documents. You can add watermarks to documents or images from a local path, as well as from a stream. For a full list of supported formats, check [Supported document formats]().

## Add a text watermark

To add a text watermark, follow these steps:

1. Open the document by passing its path (or a stream) to the [Watermarker](https://reference.groupdocs.com/watermark/python-net/) class, using a `with` block so the document is released automatically.
2. Create a [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) with the desired text and [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/).
3. Style the watermark — for example, set `foreground_color` and alignment.
4. Call `add()` to apply the watermark and `save()` to write the result.

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # Build the text watermark and style it
        watermark = TextWatermark("Top Secret", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.4

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_text_watermark()
```

  

`sample.pdf` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) to download it.

  
```text
Binary file (PDF, 352 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)

Run the program. A new watermarked document appears at the specified path.

## What's next

GroupDocs.Watermark offers many more capabilities for text watermarks — background and foreground colors, custom fonts, opacity, rotation, tiling, and absolute or relative positioning. See [Adding text watermarks]() in the advanced guide.
