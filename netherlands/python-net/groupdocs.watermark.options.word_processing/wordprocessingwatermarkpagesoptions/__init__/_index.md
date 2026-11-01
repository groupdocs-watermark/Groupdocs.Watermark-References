---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de WordProcessingWatermarkPagesOptions klasse."
type: docs
url: /nl/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de WordProcessingWatermarkPagesOptions klasse.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
import groupdocs.watermark.options.word_processing as gwo_wp

# Maak opties aan voor het toepassen van een watermerk op specifieke pagina's
options = gwo_wp.WordProcessingWatermarkPagesOptions()
options.page_numbers = [1, 3]  # target pages 1 and 3
```

### Zie ook
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)
