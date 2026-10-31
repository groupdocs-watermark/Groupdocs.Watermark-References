---
title: "metodo link_to_previous"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Collega o scollega tutti gli header e i footer ai corrispondenti header e footer nella sezione precedente."
type: docs
url: /it/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

Collega o scollega tutti gli header e i footer ai corrispondenti header e footer nella sezione precedente.

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| is_link_to_previous | `bool` | True per collegare le intestazioni e i piè di pagina alla sezione precedente; False per scollegarli. |

### Esempio

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

### Vedi anche
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
