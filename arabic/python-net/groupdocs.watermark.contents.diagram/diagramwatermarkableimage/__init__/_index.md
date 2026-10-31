---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يُنشئ نسخة جديدة من فئة DiagramWatermarkableImage باستخدام بيانات الصورة المحددة."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

ينشئ مثلاً جديداً من فئة [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) باستخدام بيانات الصورة المحددة.

```python
def __init__(self, image_data):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_data | `list[int]` | المصفوفة من البايتات غير الموقعة التي يُنشأ منها `DiagramWatermarkableImage`. |

### مثال

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

with open("test.png", "rb") as f:
    img = gwc_vsdx.DiagramWatermarkableImage(f.read())
```

### انظر أيضًا
* class [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/)
