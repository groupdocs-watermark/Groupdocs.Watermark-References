---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny instans av WordProcessingWatermarkPagesOptions-klassen."
type: docs
url: /sv/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av WordProcessingWatermarkPagesOptions-klassen.

```python
def __init__(self):
    ...
```

### Exempel

```python
import groupdocs.watermark.options.word_processing as gwo_wp

# Skapa alternativ för att applicera en vattenstämpel på specifika sidor
options = gwo_wp.WordProcessingWatermarkPagesOptions()
options.page_numbers = [1, 3]  # target pages 1 and 3
```

### Se även
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)
