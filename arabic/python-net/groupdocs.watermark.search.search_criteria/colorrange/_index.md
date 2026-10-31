---
title: "فئة ColorRange"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل نطاقًا من الألوان باستخدام تمثيل HSB للون RGB."
type: docs
url: /ar/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

يمثل نطاقًا من الألوان باستخدام تمثيل HSB للون RGB.

نوع ColorRange يكشف عن الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | ينشئ مثلاً جديدًا من الفئة [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/). |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | ينشئ مثلاً جديدًا من [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) بلون محدد دقيق. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | العلم الذي يشير إلى ما إذا كان اللون الفارغ فقط ضمن النطاق. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | القيمة النهائية للسطوع، تتراوح من 0.0 (أسود) إلى 1.0 (أبيض). |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | القيمة النهائية للدرجة اللونية، بالدرجات. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | القيمة النهائية للتشبع. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | القيمة الابتدائية للسطوع، تتراوح من 0.0 (أسود) إلى 1.0 (أبيض). |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | القيمة الابتدائية للدرجة اللونية، بالدرجات. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | القيمة الابتدائية للتشبع. |

### مثال

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# إنشاء نطاق ألوان لمطابقة لون المقدمة
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
أدلة المهام التي تستخدم `ColorRange`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### انظر أيضًا
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
