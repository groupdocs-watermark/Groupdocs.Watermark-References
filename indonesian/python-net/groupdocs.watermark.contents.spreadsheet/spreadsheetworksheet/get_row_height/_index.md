---
title: "get_row_height metode"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mengembalikan tinggi baris yang ditentukan dalam poin."
type: docs
url: /id/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

Mengembalikan tinggi baris yang ditentukan dalam poin.

```python
def get_row_height(self, row):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| row | `int` | Indeks baris. |

**Returns:** float: The height of the row in points.

### Contoh

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

### Lihat Juga
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
