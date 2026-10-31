---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يُنشئ مثيلاً جديداً من الفئة PresentationWatermarkableImage باستخدام بيانات الصورة المحددة."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

ينشئ مثلاً جديداً من فئة [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) باستخدام بيانات الصورة المحددة.

```python
def __init__(self, image_data):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_data | `list[int]` | المصفوفة من البايتات غير الموقعة التي تُستخدم لإنشاء `PresentationWatermarkableImage`. |

### مثال

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### انظر أيضًا
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
