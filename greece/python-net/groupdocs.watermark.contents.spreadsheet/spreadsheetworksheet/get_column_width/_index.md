---
title: "μέθοδος get_column_width"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Λαμβάνει το πλάτος της καθορισμένης στήλης σε μονάδες points."
type: docs
url: /el/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

Λαμβάνει το πλάτος της καθορισμένης στήλης σε μονάδες points.

```python
def get_column_width(self, column):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| column | `int` | Ο δείκτης στήλης. |

**Returns:** float: The width of the column in points.

### Παράδειγμα

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions
import groupdocs.watermark.contents.spreadsheet as gwc_xls

load_options = SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    content = watermarker.get_content()
    width = content.worksheets[0].get_column_width(0)
    print(width)
```

### Δείτε επίσης
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
