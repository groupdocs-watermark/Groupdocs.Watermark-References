---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de WordProcessingWatermarkableImage klasse met gespecificeerde afbeeldingsgegevens."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialiseert een nieuw exemplaar van de [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) klasse met opgegeven afbeeldingsgegevens.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_data | `list[int]` | De array van onondertekende bytes waaruit de `WordProcessingWatermarkableImage` wordt gemaakt. |

### Voorbeeld

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### Zie ook
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
