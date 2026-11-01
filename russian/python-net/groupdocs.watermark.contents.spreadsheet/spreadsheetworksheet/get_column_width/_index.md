---
title: "метод get_column_width"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Получает ширину указанного столбца в пунктах."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

Получает ширину указанного столбца в пунктах.

```python
def get_column_width(self, column):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| column | `int` | Индекс столбца. |

**Returns:** float: The width of the column in points.

### Пример

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

### См. также
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
