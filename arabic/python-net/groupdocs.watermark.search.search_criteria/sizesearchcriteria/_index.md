---
title: "SizeSearchCriteria فئة"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل معايير تسمح بالتصفية حسب حجم العلامة المائية."
type: docs
url: /ar/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/
is_root: false
weight: 140
---


## SizeSearchCriteria class

يمثل معايير تسمح بالتصفية حسب حجم العلامة المائية.

اعرف المزيد:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

نوع SizeSearchCriteria يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/__init__/#dimension-min-max) | ينشئ مثيلاً جديداً من فئة SizeSearchCriteria بأبعاد محددة، قيمة بداية وقيمة نهاية. |

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
| [dimension](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/dimension/) | البُعد الخاص بالعلامة المائية للبحث به. |
| [maximum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/maximum/) | قيمة النهاية. |
| [minimum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/minimum/) | قيمة البداية. |

### مثال

```python
import re
from groupdocs.watermark import Watermarker
from groupdocs.watermark.common import Dimension
from groupdocs.watermark.search.search_criteria import SizeSearchCriteria, RotateAngleSearchCriteria, TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    width_range = SizeSearchCriteria(Dimension.WIDTH, 50, 100)
    rotate_angle = RotateAngleSearchCriteria(0, 45)
    text_criteria = TextSearchCriteria(re.compile(r"^Test watermark$"))
    watermarks = watermarker.search(text_criteria.and_(width_range.or_(rotate_angle)))
    watermarks.clear()
    watermarker.save("./output.pdf")
```

### انظر أيضًا
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
