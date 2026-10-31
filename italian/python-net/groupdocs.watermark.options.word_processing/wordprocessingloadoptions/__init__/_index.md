---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe WordProcessingLoadOptions."
type: docs
url: /it/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#password}

Inizializza una nuova istanza della classe WordProcessingLoadOptions con una password specificata.

```python
def __init__(self, password):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| password | `str` | La password per aprire un contenuto crittografato. |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # esegui operazioni di filigrana
    pass
```

### Vedi anche
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
