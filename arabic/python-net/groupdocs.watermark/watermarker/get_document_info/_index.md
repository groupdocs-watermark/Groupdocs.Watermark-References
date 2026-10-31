---
title: "طريقة get_document_info"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يحصل على المعلومات حول تنسيق المستند المحمَّل."
type: docs
url: /ar/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

يحصل على المعلومات حول تنسيق المستند المحمَّل.

تعرف على المزيد حول الحصول على معلومات المستند.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### مثال

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### انظر أيضًا
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
