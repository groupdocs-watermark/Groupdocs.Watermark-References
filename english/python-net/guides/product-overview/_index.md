---
title: GroupDocs.Watermark for Python via .NET Overview
linkTitle: "Overview"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "GroupDocs.Watermark for Python via .NET adds, searches, and removes text and image watermarks across PDF, Word, Excel, PowerPoint, Visio, email, and image formats — with format-specific placement, tiling, locking, and content-tree access — on-premise, with no Microsoft Office required."
type: docs
url: /python-net/guides/product-overview/
is_root: false
weight: 90
---


## What is GroupDocs.Watermark?

GroupDocs.Watermark for Python via .NET is a native Python library that adds, searches, and removes **text and image watermarks** across PDF, Word, Excel, PowerPoint, Visio, email, and image formats. It runs entirely on-premise, requires no Microsoft Office installation, and ships as a pre-built wheel for Windows, Linux, and macOS.

Typical uses include:

- **Document security** — stamp every file in a pipeline with a "Confidential" or "Draft" mark that is hard to remove with third-party tools.
- **Branding** — overlay a logo or seal on documents and on the images embedded inside them.
- **Cleanup and migration** — find and remove outdated labels or third-party watermarks before sharing or re-publishing.
- **Compliance and tamper-resistance** — lock watermarks, add print-only PDF annotations, or rasterize pages so the watermark cannot be edited out.
- **Auditing** — search documents for existing watermarks by text, image similarity, or formatting, and report or modify them.

## Key Capabilities

| Capability | Description |
|---|---|
| **Text and image watermarks** | [Add styled text or image watermarks]() with color, opacity, rotation, alignment, and sizing. |
| **Customize and tile** | [Customize]() appearance and position, or [tile a watermark]() across the whole page. |
| **Advanced positioning** | [Absolute and relative positioning, margins, sizing, and rotation](). |
| **Format-specific placement** | PDF [artifacts/annotations](), [presentation slides](), [worksheets](), [Visio pages](), and [Word sections](). |
| **Search and modify** | [Find watermarks by text, image, or formatting](), then [modify]() or [remove]() them. |
| **Content-tree access** | Work with existing shapes, attachments, backgrounds, and headers/footers via `get_content()`. |
| **Images inside documents** | [Watermark the images embedded inside a document](). |
| **Tamper resistance** | [Lock watermarks](), protect documents, and [rasterize PDF pages](). |
| **Document inspection** | [Read file type, page count, and size]() without modifying the document. |
| **Streams** | Load input from file-like objects — handy for cloud blobs and HTTP bodies. |
| **On-premise** | No cloud calls, no Microsoft Office install, no network traffic. |

## Quick Example

Add a text watermark to a document and save the result with just a few lines of code:

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def quick_example():
    # Open the document, add a text watermark, and save the result
    with Watermarker("./document.docx") as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 36))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermarker.add(watermark)
        watermarker.save("./watermarked.docx")

if __name__ == "__main__":
    quick_example()
```

`document.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/product-overview/document.docx) to download it.

  
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/product-overview/quick_example/watermarked.docx)

For finer control, scale, rotate, and center the watermark:

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def watermark_with_options():
    with Watermarker("./document.docx") as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 36))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermark.rotate_angle = 45.0
        # Scale the watermark relative to the page and center it
        watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS
        watermark.scale_factor = 0.8
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermarker.add(watermark)
        watermarker.save("./watermarked.docx")

if __name__ == "__main__":
    watermark_with_options()
```

`document.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/product-overview/document.docx) to download it.

  
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/product-overview/watermark_with_options/watermarked.docx)

## Where to next

1. **Install the package** — [Installation]() walks through PyPI and offline wheel installation for Windows, Linux, and macOS.
2. **Add your first watermark** — [Quick Start Guide]() stamps a document in five minutes.
3. **Explore the examples** — [How to Run Examples]() clones the runnable repository and runs every documented scenario locally or in Docker.
4. **Use it in depth** — the [Developer Guide]() covers adding, customizing, searching, modifying, and removing watermarks across every supported format.
5. **Licensing** — [Licensing and Subscription]() explains evaluation mode and how to apply a license.
