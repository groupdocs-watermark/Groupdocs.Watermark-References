---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny instans av klassen DiagramWatermarkableImage med angivna bilddata."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initierar en ny instans av [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) klassen med angivna bilddata.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_data | `list[int]` | Arrayen av osignerade byte som ska användas för att skapa `DiagramWatermarkableImage`. |

### Exempel

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

with open("test.png", "rb") as f:
    img = gwc_vsdx.DiagramWatermarkableImage(f.read())
```

### Se även
* class [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/)
