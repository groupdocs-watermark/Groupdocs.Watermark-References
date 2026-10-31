---
title: "get_column_width metode"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mendapatkan lebar kolom yang ditentukan dalam poin."
type: docs
url: /id/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

Mendapatkan lebar kolom yang ditentukan dalam poin.

```python
def get_column_width(self, column):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| column | `int` | Indeks kolom. |

**Returns:** float: The width of the column in points.

### Contoh

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

### Lihat Juga
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
