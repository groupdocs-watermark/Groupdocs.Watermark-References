---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny TextWatermark med den angivna texten och teckensnittet."
type: docs
url: /sv/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text-font}

Initierar en ny TextWatermark med den angivna texten och teckensnittet.

```python
def __init__(self, text, font):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | `str` | Texten som ska användas som vattenstämpel. |
| font | `Font` | Typsnittet för texten. |

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Se även
* class [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)
