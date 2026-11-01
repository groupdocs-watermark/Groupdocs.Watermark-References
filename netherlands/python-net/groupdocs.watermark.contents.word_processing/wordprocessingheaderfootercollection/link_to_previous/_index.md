---
title: "link_to_previous methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Linkt of ontkoppelt alle kopteksten en voetteksten aan de overeenkomstige kopteksten en voetteksten in de vorige sectie."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

Linkt of ontkoppelt alle kopteksten en voetteksten aan de overeenkomstige kopteksten en voetteksten in de vorige sectie.

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| is_link_to_previous | `bool` | True om de kopteksten en voetteksten te koppelen aan de vorige sectie; False om ze te ontkoppelen. |

### Voorbeeld

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

### Zie ook
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
