---
title: "add metodu"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Yüklenen belgeye bir filigran ekler."
type: docs
url: /tr/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

Yüklenen belgeye bir filigran ekler.

GroupDocs belgelerinde filigran ekleme hakkında daha fazla bilgi edinin.

```python
def add(self, watermark):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| watermark | `Watermark` | Belgeye eklenecek filigran. |

### Örnek

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

Filigran seçeneklerini kullanarak yüklenen belgeye bir filigran ekler.

Filigran ekleme hakkında daha fazla bilgi edinin: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| watermark | `Watermark` | Belgeye eklenecek filigran. |
| options | `WatermarkOptions` | Filigranı eklerken kullanılacak ek seçenekler. |

**Returns:** None.

### Örnek

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

### Ayrıca Bakınız
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
