---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يقوم بإنشاء نسخة جديدة من الفئة WordProcessingWatermarkableImage باستخدام بيانات الصورة المحددة."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

يُنشئ مثيلاً جديدًا من الفئة [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) باستخدام بيانات الصورة المحددة.

```python
def __init__(self, image_data):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_data | `list[int]` | المصفوفة من البايتات غير الموقعة التي تُستخدم لإنشاء `WordProcessingWatermarkableImage`. |

### مثال

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### انظر أيضًا
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
