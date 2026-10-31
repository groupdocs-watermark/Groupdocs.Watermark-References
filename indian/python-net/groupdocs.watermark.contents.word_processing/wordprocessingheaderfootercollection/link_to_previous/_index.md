---
title: "link_to_previous मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "सभी हेडर और फुटर को पिछले सेक्शन के संबंधित हेडर और फुटर से लिंक या अनलिंक करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

सभी हेडर और फुटर को पिछले सेक्शन के संबंधित हेडर और फुटर से लिंक या अनलिंक करता है।

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| is_link_to_previous | `bool` | True हेडर और फुटर को पिछले सेक्शन से लिंक करने के लिए; False उन्हें अनलिंक करने के लिए। |

### उदाहरण

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

### संबंधित देखें
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
