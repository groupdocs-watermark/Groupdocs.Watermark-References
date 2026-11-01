---
title: "link_to_previous metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Länkar eller avlänkar alla sidhuvuden och sidfötter till motsvarande sidhuvuden och sidfötter i föregående avsnitt."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

Länkar eller avlänkar alla sidhuvuden och sidfötter till motsvarande sidhuvuden och sidfötter i föregående avsnitt.

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| is_link_to_previous | `bool` | True för att länka rubrikerna och sidfötterna till föregående avsnitt; False för att koppla bort dem. |

### Exempel

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

### Se även
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
