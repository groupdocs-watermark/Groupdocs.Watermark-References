---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يُنشئ مثيلاً جديدًا من Watermarker بالمسار المحدد للمستند."
type: docs
url: /ar/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

يُنشئ مثيلاً جديدًا من Watermarker بالمسار المحدد للمستند.

تعرف على المزيد حول تحميل المستندات: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار الملف لتحميل المستند منه. |

| يطرح | الوصف |
| :- | :- |
| `UnsupportedFileTypeException` | نوع المستند المقدم غير مدعوم. |
| `InvalidPasswordException` | كلمة المرور المقدمة غير صحيحة. |

### مثال

```python
from groupdocs.watermark import Watermarker

# تحميل مستند.
watermarker = Watermarker("./document.pdf")
# استخدم طرق Watermarker لإضافة أو البحث أو إزالة العلامات المائية.

# احفظ المستند.
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

يُنشئ مثيلاً جديدًا من Watermarker بالمسار المحدد للمستند وخيارات التحميل.

تعرف على المزيد حول تحميل المستندات: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار الملف لتحميل المستند منه. |
| options | `LoadOptions` | خيارات إضافية لاستخدامها عند تحميل مستند. |

| يطرح | الوصف |
| :- | :- |
| `UnsupportedFileTypeException` | نوع المستند المقدم غير مدعوم. |
| `InvalidPasswordException` | كلمة المرور المقدمة غير صحيحة. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # تنفيذ عمليات على ملف PDF المشفر
    pass
```

## __init__ {#file_path-settings}

يُنشئ Watermarker بالمسار المحدد للمستند والإعدادات.

تعرف على المزيد حول تحميل المستندات: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار الملف لتحميل المستند منه. |
| settings | `WatermarkerSettings` | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |

| يطرح | الوصف |
| :- | :- |
| `UnsupportedFileTypeException` | نوع المستند المقدم غير مدعوم. |
| `InvalidPasswordException` | كلمة المرور المقدمة غير صحيحة. |

### مثال

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import SearchableObjects
from groupdocs.watermark.search.objects import WordProcessingSearchableObjects, SpreadsheetSearchableObjects, PresentationSearchableObjects, DiagramSearchableObjects, PdfSearchableObjects

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
                     | WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=PresentationSearchableObjects.SLIDES_BACKGROUNDS
                  | PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=DiagramSearchableObjects.NONE,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    # العمل مع watermarker، على سبيل المثال، البحث أو إزالة العلامات المائية
    pass
```

## __init__ {#file_path-options-settings}

يُنشئ مثيلاً جديدًا من Watermarker بالمسار المحدد للمستند، خيارات التحميل، والإعدادات.

تعرف على المزيد حول تحميل المستندات: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار الملف لتحميل المستند منه. |
| options | `LoadOptions` | خيارات إضافية لاستخدامها عند تحميل مستند. |
| settings | `WatermarkerSettings` | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |

| يطرح | الوصف |
| :- | :- |
| `UnsupportedFileTypeException` | نوع المستند المقدم غير مدعوم. |
| `InvalidPasswordException` | كلمة المرور المقدمة غير صحيحة. |

### مثال

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.options.email import EmailLoadOptions
from groupdocs.watermark.search.search_criteria import TextSearchCriteria
from groupdocs.watermark.search.objects import SearchableObjects, EmailSearchableObjects

def search_email():
    settings = WatermarkerSettings()
    settings.searchable_objects = SearchableObjects(
        email_searchable_objects=(
            EmailSearchableObjects.Subject
            | EmailSearchableObjects.HtmlBody
            | EmailSearchableObjects.PlainTextBody
        )
    )
    load_options = EmailLoadOptions()
    with Watermarker("./test.msg", load_options, settings) as watermarker:
        criteria = TextSearchCriteria("test", False)
        watermarks = watermarker.search(criteria)
        watermarks.clear()
        watermarker.save()
```

## __init__ {#document}

يُنشئ مثيلاً جديدًا من فئة Watermarker بالـ stream المحدد.

تعرف على المزيد حول تحميل المستندات: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | الدفق لتحميل المستند منه. |

| يطرح | الوصف |
| :- | :- |
| `UnsupportedFileTypeException` | نوع المستند المقدم غير مدعوم. |
| `InvalidPasswordException` | كلمة المرور المقدمة غير صحيحة. |

### مثال

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # استخدم طرق Watermarker لإضافة أو البحث أو إزالة العلامات المائية.
            watermarker.save(output_stream)
```

## __init__ {#document-options}

يُنشئ مثيلاً جديدًا من Watermarker بالـ stream المحدد وخيارات التحميل.

تعرف على المزيد حول تحميل المستندات.

```python
def __init__(self, document, options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | الدفق لتحميل المستند منه. |
| options | `LoadOptions` | خيارات إضافية لاستخدامها عند تحميل مستند. |

| يطرح | الوصف |
| :- | :- |
| `UnsupportedFileTypeException` | نوع المستند المقدم غير مدعوم. |
| `InvalidPasswordException` | كلمة المرور المقدمة غير صحيحة. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # تنفيذ عمليات مع watermarker
        pass
```

## __init__ {#document-settings}

يُنشئ مثيلاً جديدًا من Watermarker بالـ stream المحدد والإعدادات.

تعرف على المزيد حول تحميل المستندات.

```python
def __init__(self, document, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | الدفق لتحميل المستند منه. |
| settings | `WatermarkerSettings` | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |

| يطرح | الوصف |
| :- | :- |
| `UnsupportedFileTypeException` | نوع المستند المقدم غير مدعوم. |
| `InvalidPasswordException` | كلمة المرور المقدمة غير صحيحة. |

### مثال

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import SearchableObjects
from groupdocs.watermark.search.objects import WordProcessingSearchableObjects, SpreadsheetSearchableObjects, PresentationSearchableObjects, DiagramSearchableObjects, PdfSearchableObjects

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS | WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=PresentationSearchableObjects.SLIDES_BACKGROUNDS | PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=DiagramSearchableObjects.NONE,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

for file_path in ["./document1.pdf", "./document2.docx"]:
    with open(file_path, "rb") as stream:
        with Watermarker(stream, settings) as watermarker:
            watermarks = watermarker.search()
            # العمل مع العلامات المائية المكتشفة
```

## __init__ {#document-options-settings}

يُنشئ مثيلاً جديدًا من الفئة [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) بالـ stream المحدد، خيارات التحميل والإعدادات.

تعرف على المزيد حول تحميل المستندات على https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | الدفق لتحميل المستند منه. |
| options | `LoadOptions` | خيارات إضافية لاستخدامها عند تحميل مستند. |
| settings | `WatermarkerSettings` | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |

| يطرح | الوصف |
| :- | :- |
| `UnsupportedFileTypeException` | نوع المستند المقدم غير مدعوم. |
| `InvalidPasswordException` | كلمة المرور المقدمة غير صحيحة. |

### مثال

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.options.email import EmailLoadOptions
from groupdocs.watermark.search.objects import SearchableObjects, EmailSearchableObjects
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    email_searchable_objects=(
        EmailSearchableObjects.Subject
        | EmailSearchableObjects.HtmlBody
        | EmailSearchableObjects.PlainTextBody
    )
)

load_options = EmailLoadOptions()
with open("./test.msg", "rb") as stream:
    with Watermarker(stream, load_options, settings) as watermarker:
        criteria = TextSearchCriteria("test", False)
        watermarks = watermarker.search(criteria)
        watermarks.clear()
        watermarker.save("./output.msg")
```

### انظر أيضًا
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
