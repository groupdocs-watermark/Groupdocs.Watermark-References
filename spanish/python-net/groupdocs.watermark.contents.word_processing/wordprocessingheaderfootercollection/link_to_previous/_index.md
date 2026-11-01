---
title: "link_to_previous método"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Enlaza o desenlaza todos los encabezados y pies de página con los encabezados y pies de página correspondientes en la sección anterior."
type: docs
url: /es/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

Enlaza o desenlaza todos los encabezados y pies de página con los encabezados y pies de página correspondientes en la sección anterior.

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| is_link_to_previous | `bool` | True para vincular los encabezados y pies de página a la sección anterior; False para desvincularlos. |

### Ejemplo

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

### Ver también
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
