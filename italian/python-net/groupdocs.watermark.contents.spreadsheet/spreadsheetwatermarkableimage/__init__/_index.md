---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe SpreadsheetWatermarkableImage utilizzando i dati immagine specificati."
type: docs
url: /it/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Inizializza una nuova istanza della classe [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) utilizzando i dati immagine specificati.

```python
def __init__(self, image_data):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_data | `list[int]` | L'array di byte senza segno da cui creare il `SpreadsheetWatermarkableImage`. |

### Esempio

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### Vedi anche
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
