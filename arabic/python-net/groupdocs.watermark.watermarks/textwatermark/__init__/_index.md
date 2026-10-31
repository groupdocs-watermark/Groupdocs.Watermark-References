---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يقوم بتهيئة TextWatermark جديد بالنص والخط المحددين."
type: docs
url: /ar/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text-font}

يقوم بتهيئة TextWatermark جديد بالنص والخط المحددين.

```python
def __init__(self, text, font):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | النص الذي سيُستخدم كعلامة مائية. |
| font | `Font` | خط النص. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### انظر أيضًا
* class [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)
