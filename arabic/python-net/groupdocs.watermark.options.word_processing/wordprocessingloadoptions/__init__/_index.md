---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "ينشئ نسخة جديدة من الفئة WordProcessingLoadOptions."
type: docs
url: /ar/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديداً من الفئة [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#password}

ينشئ مثيلاً جديداً من فئة WordProcessingLoadOptions باستخدام كلمة مرور محددة.

```python
def __init__(self, password):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| password | `str` | كلمة المرور لفتح محتوى مشفر. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # تنفيذ عمليات العلامة المائية
    pass
```

### انظر أيضًا
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
