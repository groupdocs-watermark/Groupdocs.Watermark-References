---
title: "méthode link_to_previous"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Lie ou délie tous les en-têtes et pieds de page aux en-têtes et pieds de page correspondants de la section précédente."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

Lie ou délie tous les en-têtes et pieds de page aux en-têtes et pieds de page correspondants de la section précédente.

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| is_link_to_previous | `bool` | True pour lier les en-têtes et pieds de page à la section précédente ; False pour les délier. |

### Exemple

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

### Voir aussi
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
