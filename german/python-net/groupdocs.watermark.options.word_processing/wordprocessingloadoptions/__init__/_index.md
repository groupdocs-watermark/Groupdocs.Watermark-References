---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse WordProcessingLoadOptions."
type: docs
url: /de/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) Klasse.

```python
def __init__(self):
    ...
```

## __init__ {#password}

Initialisiert eine neue Instanz der Klasse WordProcessingLoadOptions mit einem angegebenen Passwort.

```python
def __init__(self, password):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| password | `str` | Das Passwort zum Öffnen eines verschlüsselten Inhalts. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # Wasserzeichenoperationen ausführen
    pass
```

### Siehe auch
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
