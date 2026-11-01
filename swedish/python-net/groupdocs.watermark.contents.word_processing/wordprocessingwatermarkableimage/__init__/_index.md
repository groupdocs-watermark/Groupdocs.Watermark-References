---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny instans av WordProcessingWatermarkableImage-klassen med angivna bilddata."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initierar en ny instans av klassen [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) med angivna bilddata.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_data | `list[int]` | Den array av osignerade byte som ska användas för att skapa `WordProcessingWatermarkableImage`. |

### Exempel

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### Se även
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
