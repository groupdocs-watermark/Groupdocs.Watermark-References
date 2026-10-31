---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der WordProcessingWatermarkableImage Klasse mit den angegebenen Bilddaten."
type: docs
url: /de/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialisiert eine neue Instanz der [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) Klasse mit den angegebenen Bilddaten.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_data | `list[int]` | Das Array aus vorzeichenlosen Bytes, aus dem das `WordProcessingWatermarkableImage` erstellt wird. |

### Beispiel

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### Siehe auch
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
