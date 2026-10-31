---
title: "فئة WatermarkerSettings"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يحدد الإعدادات لتخصيص سلوك Watermarker."
type: docs
url: /ar/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

يحدد الإعدادات لتخصيص سلوك Watermarker.

يعرض نوع WatermarkerSettings الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | يُهيئ نسخة جديدة من WatermarkerSettings. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | المسجل المستخدم لتسجيل الأحداث والأخطاء أثناء وضع العلامة المائية. |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | الكائنات القابلة للبحث التي يجب تضمينها في بحث العلامة المائية. |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | يحصل على القيمة الافتراضية للفئة. |

### مثال

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import (
    SearchableObjects, WordProcessingSearchableObjects, PdfSearchableObjects,
)

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
    | WordProcessingSearchableObjects.TEXT,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    possible = watermarker.search()
    print("Found", len(possible), "possible watermark(s)")
```

### Guides
أدلة المهام التي تستخدم `WatermarkerSettings`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### انظر أيضًا
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
