---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe WordProcessingWatermarkPagesOptions."
type: docs
url: /it/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe WordProcessingWatermarkPagesOptions.

```python
def __init__(self):
    ...
```

### Esempio

```python
import groupdocs.watermark.options.word_processing as gwo_wp

# Crea opzioni per applicare un watermark a pagine specifiche
options = gwo_wp.WordProcessingWatermarkPagesOptions()
options.page_numbers = [1, 3]  # target pages 1 and 3
```

### Vedi anche
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)
