---
title: "طريقة protect"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يحمي المستند من التغييرات ويحدد كلمة مرور الحماية."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

يحمي المستند من التغييرات ويحدد كلمة مرور الحماية.

لجعل محتوى المستند قابلاً للتحرير، استخدم الطريقة المناسبة لإضافة علامة مائية مع المعامل `WordProcessingLockType.allow_only_form_fields` أو `WordProcessingLockType.read_only_with_editable_content`.

```python
def protect(self, protection_type, password):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | يحدد نوع الحماية للمستند. |
| password | `str` | كلمة المرور لحماية المستند. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
from groupdocs.watermark.contents.word_processing import WordProcessingProtectionType

def protect_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.protect(WordProcessingProtectionType.READ_ONLY, "p@ssw0rd")
        watermarker.save("./output.docx")
```

### انظر أيضًا
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
