---
title: "remove-metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Tar bort ett vattenmärke från dokumentet."
type: docs
url: /sv/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

Tar bort ett vattenmärke från dokumentet.

Läs mer om att ta bort vattenstämplar: Ta bort hittade vattenstämplar.

```python
def remove(self, possible_watermark):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | Vattenstämpeln att ta bort. |

### Exempel

```python
from groupdocs.watermark import Watermarker

def remove_first_watermark():
    with Watermarker("./document.pdf") as watermarker:
        watermarks = watermarker.search()
        if watermarks:
            watermarker.remove(watermarks[0])
        watermarker.save("./output.pdf")
```

## remove {#possible_watermarks}

Tar bort alla vattenmärken i samlingen från dokumentet.

Läs mer om att ta bort vattenstämplar i GroupDocs-dokumentationen.

```python
def remove(self, possible_watermarks):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | Samlingen av vattenstämplar att ta bort. |

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # Ta bort i omvänd ordning för att hålla indexen giltiga
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### Se även
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
