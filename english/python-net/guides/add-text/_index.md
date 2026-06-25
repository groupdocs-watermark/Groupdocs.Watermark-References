---
title: Add text watermarks
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/guides/add-text/
is_root: false
weight: 10
---


One of the main features of the GroupDocs.Watermark library is adding text watermarks to documents. You may add watermarks to documents or images from local disks, as well as from streams. For a full list of supported document formats, check [Supported formats]().

To add a text watermark perform follow next code sample:

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.common as gwс

def run():
  with gw.Watermarker("sample.docx") as watermarker:
      font = gww.Font("Arial", 36.0)
      watermark = gww.TextWatermark("top secret", font)
      watermark.foreground_color = gww.Color.red;
      watermark.horizontal_alignment = gwс.HorizontalAlignment.CENTER
      watermark.vertical_alignment = gwс.VerticalAlignment.CENTER

      watermarker.add(watermark)
      watermarker.save(join(output_directory, "result.docx"))
```

Run the program. A new watermarked document will appear in the specified path.

### What's next

GroupDocs.Watermark offers many more capabilities for adding text watermarks. For example, it allows specifying background and foreground colors, formatting, text opacity, use of absolute or relative positioning, and so on.
