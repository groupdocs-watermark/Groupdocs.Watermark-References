---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen metin ve yazı tipi ile yeni bir TextWatermark başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text-font}

Belirtilen metin ve yazı tipi ile yeni bir TextWatermark başlatır.

```python
def __init__(self, text, font):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | `str` | Filigran olarak kullanılacak metin. |
| font | `Font` | Metnin yazı tipi. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Ayrıca Bakınız
* class [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)
