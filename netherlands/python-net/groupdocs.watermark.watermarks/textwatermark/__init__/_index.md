---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuwe TextWatermark met de opgegeven tekst en lettertype."
type: docs
url: /nl/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text-font}

Initialiseert een nieuwe TextWatermark met de opgegeven tekst en lettertype.

```python
def __init__(self, text, font):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | De tekst die als watermerk wordt gebruikt. |
| font | `Font` | Het lettertype van de tekst. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Zie ook
* class [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)
