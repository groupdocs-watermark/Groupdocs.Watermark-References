---
title: "طريقة add"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يضيف علامة مائية إلى المستند المحمَّل."
type: docs
url: /ar/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

يضيف علامة مائية إلى المستند المحمَّل.

تعرف على المزيد حول إضافة العلامات المائية في وثائق GroupDocs.

```python
def add(self, watermark):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| watermark | `Watermark` | العلامة المائية لإضافتها إلى المستند. |

### مثال

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

يضيف علامة مائية إلى المستند المحمَّل باستخدام خيارات العلامة المائية.

تعرف على المزيد حول إضافة العلامات المائية: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| watermark | `Watermark` | العلامة المائية لإضافتها إلى المستند. |
| options | `WatermarkOptions` | خيارات إضافية لاستخدامها عند إضافة العلامة المائية. |

**Returns:** None.

### مثال

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

### انظر أيضًا
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
