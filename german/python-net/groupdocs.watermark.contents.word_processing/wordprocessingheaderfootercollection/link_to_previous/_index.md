---
title: "link_to_previous Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Verknüpft oder löst alle Kopf- und Fußzeilen mit den entsprechenden Kopf- und Fußzeilen im vorherigen Abschnitt."
type: docs
url: /de/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

Verknüpft oder löst alle Kopf- und Fußzeilen mit den entsprechenden Kopf- und Fußzeilen im vorherigen Abschnitt.

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| is_link_to_previous | `bool` | True, um die Kopf- und Fußzeilen mit dem vorherigen Abschnitt zu verknüpfen; False, um sie zu lösen. |

### Beispiel

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

### Siehe auch
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
