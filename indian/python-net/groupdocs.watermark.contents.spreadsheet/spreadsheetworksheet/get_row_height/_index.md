---
title: "get_row_height मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट पंक्ति की ऊँचाई को पॉइंट्स में लौटाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

निर्दिष्ट पंक्ति की ऊँचाई को पॉइंट्स में लौटाता है।

```python
def get_row_height(self, row):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| row | `int` | पंक्ति इंडेक्स। |

**Returns:** float: The height of the row in points.

### उदाहरण

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

### संबंधित देखें
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
