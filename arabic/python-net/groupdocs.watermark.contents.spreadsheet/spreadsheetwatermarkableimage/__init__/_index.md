---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يُنشئ مثيلاً جديدًا من الفئة SpreadsheetWatermarkableImage باستخدام بيانات الصورة المحددة."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

ينشئ مثلاً جديداً من فئة [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) باستخدام بيانات الصورة المحددة.

```python
def __init__(self, image_data):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| image_data | `list[int]` | المصفوفة من البايتات غير الموقعة التي يُنشأ منها `SpreadsheetWatermarkableImage`. |

### مثال

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### انظر أيضًا
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
