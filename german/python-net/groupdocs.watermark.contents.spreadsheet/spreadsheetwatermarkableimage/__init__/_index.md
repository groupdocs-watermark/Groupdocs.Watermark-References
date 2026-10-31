---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse **SpreadsheetWatermarkableImage** mit den angegebenen Bilddaten."
type: docs
url: /de/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initialisiert eine neue Instanz der Klasse [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) mit den angegebenen Bilddaten.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_data | `list[int]` | Das Array aus vorzeichenlosen Bytes, aus dem das `SpreadsheetWatermarkableImage` erstellt wird. |

### Beispiel

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### Siehe auch
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
