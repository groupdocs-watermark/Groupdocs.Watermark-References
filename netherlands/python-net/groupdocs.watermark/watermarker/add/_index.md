---
title: "add methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Voegt een watermerk toe aan het geladen document."
type: docs
url: /nl/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

Voegt een watermerk toe aan het geladen document.

Meer informatie over het toevoegen van watermerken in de GroupDocs-documentatie.

```python
def add(self, watermark):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| watermark | `Watermark` | Het watermerk om toe te voegen aan het document. |

### Voorbeeld

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

Voegt een watermerk toe aan het geladen document met behulp van watermerkopties.

Meer informatie over het toevoegen van watermerken: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| watermark | `Watermark` | Het watermerk om toe te voegen aan het document. |
| options | `WatermarkOptions` | Aanvullende opties om te gebruiken bij het toevoegen van het watermerk. |

**Returns:** None.

### Voorbeeld

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

### Zie ook
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
