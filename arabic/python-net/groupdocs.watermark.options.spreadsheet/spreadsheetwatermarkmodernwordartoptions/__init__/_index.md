---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "ينشئ مثيلاً جديداً من الفئة SpreadsheetWatermarkModernWordArtOptions."
type: docs
url: /ar/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثلاً جديداً من الفئة [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/).

```python
def __init__(self):
    ...
```

### مثال

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

### انظر أيضًا
* class [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/)
