---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny instans av klassen WordProcessingLoadOptions."
type: docs
url: /sv/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) klassen.

```python
def __init__(self):
    ...
```

## __init__ {#password}

Initierar en ny instans av WordProcessingLoadOptions-klassen med ett angivet lösenord.

```python
def __init__(self, password):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| password | `str` | Lösenordet för att öppna krypterat innehåll. |

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # utför vattenstämpeloperationer
    pass
```

### Se även
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
