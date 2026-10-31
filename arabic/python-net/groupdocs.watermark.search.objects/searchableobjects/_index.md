---
title: "فئة SearchableObjects"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يحدد كائنات المستند التي يجب تضمينها في بحث العلامة المائية."
type: docs
url: /ar/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

يحدد كائنات المستند التي يجب تضمينها في بحث العلامة المائية.

اعرف المزيد:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

نوع SearchableObjects يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | يُنشئ مثلاً جديداً من الفئة [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | الكائنات داخل مستند Visio التي يجب تضمينها في بحث العلامة المائية. |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | الكائنات داخل رسالة بريد إلكتروني التي يجب تضمينها في بحث العلامة المائية. |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | الكائنات داخل مستند PDF التي يجب تضمينها في بحث العلامة المائية. |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | الكائنات داخل مستند PowerPoint التي يجب تضمينها في بحث العلامة المائية. |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | الكائنات داخل مستند Excel التي يجب تضمينها في بحث العلامة المائية. |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | الكائنات داخل مستند Word التي يجب تضمينها في بحث العلامة المائية. |

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
دليل المهام الذي يستخدم `SearchableObjects`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### انظر أيضًا
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
