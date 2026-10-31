---
title: "خاصية create_page_stream"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "المندوب المسؤول عن إنشاء تدفق الصفحة المستخدم للحصول على تدفق قابل للكتابة لكل صفحة مُعالجة."
type: docs
url: /ar/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

المندوب المسؤول عن إنشاء تدفق الصفحة المستخدم للحصول على تدفق قابل للكتابة لكل صفحة مُعالجة.

يقوم GroupDocs.Watermark بتحويل صفحات المستند إلى صور. قدّم Callable يستقبل رقم الصفحة (`int`) ويعيد تدفق `io.RawIOBase` قابل للكتابة؛ تقوم المكتبة بكتابة الصورة المرسومة إلى التدفق وتغلقه.

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### انظر أيضًا
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
