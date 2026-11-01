---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса SpreadsheetTextEffects."
type: docs
url: /ru/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса [`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/).

```python
def __init__(self):
    ...
```

### Пример

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

### См. также
* class [`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/)
