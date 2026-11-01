---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny instans av PresentationWatermarkableImage‑klassen med angivna bilddata."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initierar en ny instans av klassen [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) med angivna bilddata.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_data | `list[int]` | Arrayen av osignerade byte som ska användas för att skapa `PresentationWatermarkableImage`. |

### Exempel

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### Se även
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
