---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de la classe WordProcessingWatermarkPagesOptions."
type: docs
url: /fr/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe WordProcessingWatermarkPagesOptions.

```python
def __init__(self):
    ...
```

### Exemple

```python
import groupdocs.watermark.options.word_processing as gwo_wp

# Créer des options pour appliquer un filigrane à des pages spécifiques
options = gwo_wp.WordProcessingWatermarkPagesOptions()
options.page_numbers = [1, 3]  # target pages 1 and 3
```

### Voir aussi
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)
