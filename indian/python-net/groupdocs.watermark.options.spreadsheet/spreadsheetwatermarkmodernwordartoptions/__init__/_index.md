---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "SpreadsheetWatermarkModernWordArtOptions क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/__init__/
is_root: false
weight: 10
---


## __init__

[`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/) वर्ग का एक नया उदाहरण प्रारंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

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

### संबंधित देखें
* class [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/)
