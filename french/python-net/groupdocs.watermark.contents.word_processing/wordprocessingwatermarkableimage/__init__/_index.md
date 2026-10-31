---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de la classe WordProcessingWatermarkableImage en utilisant les données d'image spécifiées."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialise une nouvelle instance de la classe [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) en utilisant les données d'image spécifiées.

```python
def __init__(self, image_data):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| image_data | `list[int]` | Le tableau d'octets non signés à partir duquel créer le `WordProcessingWatermarkableImage`. |

### Exemple

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### Voir aussi
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
