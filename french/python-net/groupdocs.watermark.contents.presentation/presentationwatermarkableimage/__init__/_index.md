---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de la classe PresentationWatermarkableImage en utilisant les données d'image spécifiées."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialise une nouvelle instance de la classe [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) en utilisant les données d'image spécifiées.

```python
def __init__(self, image_data):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| image_data | `list[int]` | Le tableau d'octets non signés à partir duquel créer le `PresentationWatermarkableImage`. |

### Exemple

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### Voir aussi
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
