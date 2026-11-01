---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de DiagramWatermarkableImage-klasse met opgegeven afbeeldingsgegevens."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialiseert een nieuw exemplaar van de [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) klasse met de opgegeven afbeeldingsgegevens.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_data | `list[int]` | De array van onondertekende bytes waaruit de `DiagramWatermarkableImage` wordt gemaakt. |

### Voorbeeld

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

with open("test.png", "rb") as f:
    img = gwc_vsdx.DiagramWatermarkableImage(f.read())
```

### Zie ook
* class [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/)
