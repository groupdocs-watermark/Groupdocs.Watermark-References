---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuwe instantie van de WordProcessingLoadOptions‑klasse."
type: docs
url: /nl/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) klasse.

```python
def __init__(self):
    ...
```

## __init__ {#password}

Initialiseert een nieuw exemplaar van de WordProcessingLoadOptions klasse met een opgegeven wachtwoord.

```python
def __init__(self, password):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| password | `str` | Het wachtwoord voor het openen van versleutelde inhoud. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # voert watermerkbewerkingen uit
    pass
```

### Zie ook
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
