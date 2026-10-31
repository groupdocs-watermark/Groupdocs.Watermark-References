---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de la classe WordProcessingLoadOptions."
type: docs
url: /fr/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#password}

Initialise une nouvelle instance de la classe WordProcessingLoadOptions avec un mot de passe spécifié.

```python
def __init__(self, password):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| password | `str` | Le mot de passe pour ouvrir un contenu chiffré. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # effectuer des opérations de filigrane
    pass
```

### Voir aussi
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
