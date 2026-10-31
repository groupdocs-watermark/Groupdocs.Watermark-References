---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der DiagramWatermarkableImage-Klasse mit den angegebenen Bilddaten."
type: docs
url: /de/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialisiert eine neue Instanz der Klasse [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) mit angegebenen Bilddaten.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_data | `list[int]` | Das Array aus vorzeichenlosen Bytes, aus dem das `DiagramWatermarkableImage` erstellt wird. |

### Beispiel

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

with open("test.png", "rb") as f:
    img = gwc_vsdx.DiagramWatermarkableImage(f.read())
```

### Siehe auch
* class [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/)
