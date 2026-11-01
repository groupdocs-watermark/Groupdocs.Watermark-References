---
title: "метод get_row_height"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Возвращает высоту указанной строки в пунктах."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

Возвращает высоту указанной строки в пунктах.

```python
def get_row_height(self, row):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| row | `int` | Индекс строки. |

**Returns:** float: The height of the row in points.

### Пример

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions
    import groupdocs.watermark.contents.spreadsheet as gwc_xls

    load_options = SpreadsheetLoadOptions()
    with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
        content = watermarker.get_content()
        height = content.worksheets[0].get_row_height(0)
        print(height)
    ```

### См. также
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
