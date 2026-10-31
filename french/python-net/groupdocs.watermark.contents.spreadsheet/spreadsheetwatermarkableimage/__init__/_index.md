---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de la classe SpreadsheetWatermarkableImage en utilisant les données d'image spécifiées."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialise une nouvelle instance de la classe [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) en utilisant les données d'image spécifiées.

```python
def __init__(self, image_data):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| image_data | `list[int]` | Le tableau d'octets non signés à partir duquel créer le `SpreadsheetWatermarkableImage`. |

### Exemple

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### Voir aussi
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
