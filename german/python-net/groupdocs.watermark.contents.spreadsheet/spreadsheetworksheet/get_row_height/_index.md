---
title: "get_row_height Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Gibt die Höhe der angegebenen Zeile in Punkten zurück."
type: docs
url: /de/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

Gibt die Höhe der angegebenen Zeile in Punkten zurück.

```python
def get_row_height(self, row):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| row | `int` | Der Zeilenindex. |

**Returns:** float: The height of the row in points.

### Beispiel

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

### Siehe auch
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
