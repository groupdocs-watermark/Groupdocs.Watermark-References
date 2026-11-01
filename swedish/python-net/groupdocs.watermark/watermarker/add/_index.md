---
title: "lägg till metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Lägger till ett vattenmärke i det inlästa dokumentet."
type: docs
url: /sv/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

Lägger till ett vattenmärke i det inlästa dokumentet.

Läs mer om att lägga till vattenstämplar i GroupDocs-dokumentationen.

```python
def add(self, watermark):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| watermark | `Watermark` | Vattenstämpeln att lägga till i dokumentet. |

### Exempel

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

Lägger till ett vattenmärke i det inlästa dokumentet med hjälp av vattenmärkesalternativ.

Läs mer om att lägga till vattenstämplar: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| watermark | `Watermark` | Vattenstämpeln att lägga till i dokumentet. |
| options | `WatermarkOptions` | Ytterligare alternativ att använda när vattenstämpeln läggs till. |

**Returns:** None.

### Exempel

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

### Se även
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
