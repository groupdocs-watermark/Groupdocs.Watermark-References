---
title: "طريقة get_row_height"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يعيد ارتفاع الصف المحدد بالنقاط."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

يعيد ارتفاع الصف المحدد بالنقاط.

```python
def get_row_height(self, row):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| row | `int` | مؤشر الصف. |

**Returns:** float: The height of the row in points.

### مثال

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

### انظر أيضًا
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
