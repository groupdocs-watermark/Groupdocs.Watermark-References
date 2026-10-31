---
title: "فئة MeasureValue"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل قيمة قياس بنوع محدد وقيمة عددية."
type: docs
url: /ar/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

يمثل قيمة قياس بنوع محدد وقيمة عددية.

يعرض نوع MeasureValue الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | نوع القياس. |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | القيمة العددية للقياس؛ يجب أن تكون أكبر من 0. |

### مثال

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# إنشاء قياس معبر عنه كنسبة مئوية من الصفحة
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
أدلة المهام التي تستخدم `MeasureValue`:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### انظر أيضًا
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
