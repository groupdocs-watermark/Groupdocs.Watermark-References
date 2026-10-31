---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse PresentationWatermarkableImage mit den angegebenen Bilddaten."
type: docs
url: /de/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialisiert eine neue Instanz der Klasse [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) mit den angegebenen Bilddaten.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_data | `list[int]` | Das Array aus vorzeichenlosen Bytes, aus dem das `PresentationWatermarkableImage` erstellt werden soll. |

### Beispiel

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### Siehe auch
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
