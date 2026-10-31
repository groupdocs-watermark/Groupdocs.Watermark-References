---
title: "فئة VectorSearchCriteria"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل معايير تسمح بالتصفية حسب لون العلامة المائية."
type: docs
url: /ar/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/
is_root: false
weight: 170
---


## VectorSearchCriteria class

يمثل معايير تسمح بالتصفية حسب لون العلامة المائية.

اعرف المزيد:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

نوع VectorSearchCriteria يكشف عن الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/__init__/) | يُنشئ مثيلًا جديدًا لـ [`VectorSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/). |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | يجمع هذا SearchCriteria مع معايير أخرى باستخدام عامل AND المنطقي. (موروث من [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (موروث من [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | ينفي هذا SearchCriteria. (موروث من [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | يجمع هذا SearchCriteria مع معايير أخرى باستخدام عامل OR المنطقي. (موروث من [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (موروث من [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [vector_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/vector_color_range/) | نطاق الألوان المستخدم لتصفية العلامات المائية المتجهية حسب لون المقدمة. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import VectorSearchCriteria, ColorRange
from groupdocs.watermark.watermarks import Color

with Watermarker("./document.pdf") as watermarker:
    search_criteria = VectorSearchCriteria()
    watermark_color = Color.from_argb(255, 169, 170, 174)  # #a9aaae
    color_range = ColorRange(watermark_color)
    color_range.min_brightness = 0.1
    color_range.max_brightness = 0.7
    search_criteria.vector_color_range = color_range

    possible_watermarks = watermarker.search(search_criteria)
    possible_watermarks.clear()
    watermarker.save("./output.pdf")
```

### انظر أيضًا
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
