---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse WordProcessingWatermarkPagesOptions."
type: docs
url: /de/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der Klasse WordProcessingWatermarkPagesOptions.

```python
def __init__(self):
    ...
```

### Beispiel

```python
import groupdocs.watermark.options.word_processing as gwo_wp

# Optionen erstellen, um ein Wasserzeichen auf bestimmten Seiten anzuwenden
options = gwo_wp.WordProcessingWatermarkPagesOptions()
options.page_numbers = [1, 3]  # target pages 1 and 3
```

### Siehe auch
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)
