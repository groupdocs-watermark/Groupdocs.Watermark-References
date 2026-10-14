---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes a new TextWatermark with the specified text and font."
type: docs
url: /python-net/groupdocs.watermark.watermarks/textwatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text-font}

Initializes a new TextWatermark with the specified text and font.

```python
def __init__(self, text, font):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | The text to be used as watermark. |
| font | `Font` | The font of the text. |

### Example

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### See Also
* class [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)
