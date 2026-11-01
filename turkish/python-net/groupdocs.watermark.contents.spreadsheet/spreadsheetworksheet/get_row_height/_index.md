---
title: "get_row_height yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen satırın yüksekliğini nokta cinsinden döndürür."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

Belirtilen satırın yüksekliğini nokta cinsinden döndürür.

```python
def get_row_height(self, row):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| row | `int` | Satır indeksi. |

**Returns:** float: The height of the row in points.

### Örnek

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

### Ayrıca Bakınız
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
