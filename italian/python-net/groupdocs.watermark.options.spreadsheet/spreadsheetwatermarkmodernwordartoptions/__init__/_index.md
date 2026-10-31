---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe SpreadsheetWatermarkModernWordArtOptions."
type: docs
url: /it/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/).

```python
def __init__(self):
    ...
```

### Esempio

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls

load_options = gwo_xls.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    text_watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))
    options = gwo_xls.SpreadsheetWatermarkModernWordArtOptions()
    options.worksheet_index = 0
    watermarker.add(text_watermark, options)
    watermarker.save("output.xlsx")
```

### Vedi anche
* class [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/)
