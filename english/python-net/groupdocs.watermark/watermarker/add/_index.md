---
title: add method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

Adds a watermark to the loaded document.

Learn more about adding watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| watermark | `Watermark` | The watermark to add to the document. |

### Example

```python
import io
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww

with open("watermark.jpg", "rb") as f:
    data = f.read()

with gw.Watermarker("image.png") as watermarker:
    with gww.ImageWatermark(io.BytesIO(data)) as watermark:
        watermarker.add(watermark)
    watermarker.save("image.png")
```

## add {#watermark-options}

Adds a watermark to the loaded document using watermark options.

Learn more about adding watermarks.

```python
def add(self, watermark, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| watermark | `Watermark` | The watermark to add to the document. |
| options | `WatermarkOptions` | Additional options to use when adding the watermark. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.pdf as gwo_pdf

load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    with gww.ImageWatermark("watermark.png") as watermark:
        options = gwo_pdf.PdfXObjectWatermarkOptions()
        options.page_index = 0
        watermarker.add(watermark, options)
    watermarker.save("document.pdf")
```

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
