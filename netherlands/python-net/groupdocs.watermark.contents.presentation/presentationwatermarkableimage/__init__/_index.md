---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de PresentationWatermarkableImage-klasse met opgegeven afbeeldingsgegevens."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialiseert een nieuw exemplaar van de [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) klasse met opgegeven afbeeldingsgegevens.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_data | `list[int]` | De array van ongetekende bytes waaruit de `PresentationWatermarkableImage` wordt gemaakt. |

### Voorbeeld

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### Zie ook
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
