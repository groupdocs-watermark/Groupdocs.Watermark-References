---
title: add method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Adds a watermark to the loaded document."
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
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
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
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
