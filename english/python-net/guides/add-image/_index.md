---
title: Add image watermarks
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/guides/add-image/
is_root: false
weight: 130
---


One of the main features of the GroupDocs.Watermark library is adding image watermarks to documents. You may add watermarks to documents or images from local disks, as well as from streams. For a full list of supported document formats, check [Supported formats]().

To add an image watermark perform the following sample:

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.common as gwс

def run():
  with gw.Watermarker("sample.xlsx") as watermarker:
      watermark = gww.ImageWatermark("logo.png")
      watermark.horizontal_alignment = gwс.HorizontalAlignment.CENTER
      watermark.vertical_alignment = gwс.VerticalAlignment.CENTER

      watermarker.add(watermark)
      watermarker.save(join(output_directory, "result.xlsx"))
```

### What's next

GroupDocs.Watermark offers many more capabilities for adding image watermarks. It's possible  from streams, use absolute or relative positioning, and so on.
