---
title: "طريقة unprotect"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يزيل الحماية من المستند بغض النظر عن كلمة المرور."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/
is_root: false
weight: 1090
---


## unprotect

يزيل الحماية من المستند بغض النظر عن كلمة المرور.

```python
def unprotect(self):
    ...
```

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def unprotect_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.unprotect()
        watermarker.save("./output.docx")

if __name__ == "__main__":
    unprotect_document()
```

### انظر أيضًا
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
