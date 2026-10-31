---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance baru dari kelas SpreadsheetWatermarkModernWordArtOptions."
type: docs
url: /id/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari kelas [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/).

```python
def __init__(self):
    ...
```

### Contoh

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

### Lihat Juga
* class [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/)
