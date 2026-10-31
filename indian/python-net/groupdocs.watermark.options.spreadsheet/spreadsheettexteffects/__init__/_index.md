---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "SpreadsheetTextEffects क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/__init__/
is_root: false
weight: 10
---


## __init__

[`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/) वर्ग का एक नया उदाहरण प्रारंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls
import groupdocs.watermark.common as gwc
from groupdocs.watermark.contents import OfficeDashStyle, OfficeLineStyle

load_options = gwo_xls.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Segoe UI", 19.0))
    effects = gwo_xls.SpreadsheetTextEffects()
    effects.line_format.enabled = True
    effects.line_format.color = gww.Color.red
    effects.line_format.dash_style = OfficeDashStyle.DASH_DOT_DOT
    effects.line_format.line_style = OfficeLineStyle.TRIPLE
    effects.line_format.weight = 1
    options = gwo_xls.SpreadsheetWatermarkShapeOptions()
    options.effects = effects
    watermarker.add(watermark, options)
    watermarker.save("output.xlsx")
```

### संबंधित देखें
* class [`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/)
