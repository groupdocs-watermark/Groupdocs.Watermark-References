---
title: "μέθοδος get_row_height"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Επιστρέφει το ύψος της καθορισμένης γραμμής σε σημεία."
type: docs
url: /el/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

Επιστρέφει το ύψος της καθορισμένης γραμμής σε σημεία.

```python
def get_row_height(self, row):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| row | `int` | Ο δείκτης γραμμής. |

**Returns:** float: The height of the row in points.

### Παράδειγμα

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

### Δείτε επίσης
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
