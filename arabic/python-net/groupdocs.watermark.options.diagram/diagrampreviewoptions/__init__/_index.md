---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "ينشئ مثيلاً جديداً من الفئة DiagramPreviewOptions مع إغلاق تدفق الإخراج."
type: docs
url: /ar/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

يُنشئ مثيلًا جديدًا للفئة [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/) مما يؤدي إلى إغلاق تدفق الإخراج.

```python
def __init__(self, create_page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | ينشئ تدفقًا لمعاينة صفحة محددة. |

## __init__ {#create_page_stream-release_page_stream}

يُنشئ مثيلًا جديدًا لـ [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/) مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل لاستخدامه لاحقًا.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | ينشئ تدفقًا لمعاينة صفحة محددة. |
| release_page_stream | `ReleasePageStream` | يُخطر بأن إنشاء معاينة الصفحة انتهى ويحصل على تدفق الإخراج. |

### انظر أيضًا
* class [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/)
