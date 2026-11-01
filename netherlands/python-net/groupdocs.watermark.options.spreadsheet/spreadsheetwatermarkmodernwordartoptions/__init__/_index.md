---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de SpreadsheetWatermarkModernWordArtOptions-klasse."
type: docs
url: /nl/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/) klasse.

```python
def __init__(self):
    ...
```

### Voorbeeld

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

### Zie ook
* class [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/)
