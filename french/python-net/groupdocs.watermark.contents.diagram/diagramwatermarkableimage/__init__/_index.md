---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de la classe DiagramWatermarkableImage en utilisant les données d'image spécifiées."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialise une nouvelle instance de la classe [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) en utilisant les données d'image spécifiées.

```python
def __init__(self, image_data):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| image_data | `list[int]` | Le tableau d'octets non signés à partir duquel créer le `DiagramWatermarkableImage`. |

### Exemple

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

with open("test.png", "rb") as f:
    img = gwc_vsdx.DiagramWatermarkableImage(f.read())
```

### Voir aussi
* class [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/)
