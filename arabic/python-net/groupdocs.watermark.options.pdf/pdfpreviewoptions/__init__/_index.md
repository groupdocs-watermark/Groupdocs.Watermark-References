---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يُنشئ مثلاً جديداً من الفئة PdfPreviewOptions مما يؤدي إلى إغلاق تدفق الإخراج."
type: docs
url: /ar/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

يقوم بتهيئة نسخة جديدة من الفئة [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/) بحيث يتم إغلاق تدفق الإخراج.

```python
def __init__(self, create_page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | ينشئ تدفقًا لمعاينة صفحة محددة. |

## __init__ {#create_page_stream-release_page_stream}

يقوم بتهيئة نسخة جديدة من PdfPreviewOptions تُعيد تدفق الإخراج إلى العميل للاستخدام لاحقًا.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | ينشئ تدفقًا لمعاينة صفحة محددة. |
| release_page_stream | `ReleasePageStream` | يُخطر بأن إنشاء معاينة الصفحة انتهى ويحصل على تدفق الإخراج. |

### انظر أيضًا
* class [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/)
