---
title: "get_column_width yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen sütunun puan cinsinden genişliğini alır."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

Belirtilen sütunun puan cinsinden genişliğini alır.

```python
def get_column_width(self, column):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| column | `int` | Sütun indeksi. |

**Returns:** float: The width of the column in points.

### Örnek

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

### Ayrıca Bakınız
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
