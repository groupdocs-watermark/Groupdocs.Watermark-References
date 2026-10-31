---
title: "link_to_previous طريقة"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يربط أو يفك ربط جميع رؤوس وتذييلات إلى الرؤوس والتذييلات المقابلة في القسم السابق."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

يربط أو يفك ربط جميع رؤوس وتذييلات إلى الرؤوس والتذييلات المقابلة في القسم السابق.

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| is_link_to_previous | `bool` | True لربط رؤوس وتذييلات القسم السابق؛ False لإلغاء ربطها. |

### مثال

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
import groupdocs.watermark.contents.word_processing as wp

load_options = WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    content = watermarker.get_content()
    for i in range(1, content.sections.count):
        content.sections[i].headers_footers.link_to_previous(True)
    watermarker.save("output.docx")
```

### انظر أيضًا
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
