---
title: "get_column_width मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट कॉलम की चौड़ाई पॉइंट्स में प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_column_width/
is_root: false
weight: 1010
---


## get_column_width {#column}

निर्दिष्ट कॉलम की चौड़ाई पॉइंट्स में प्राप्त करता है।

```python
def get_column_width(self, column):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| column | `int` | कॉलम इंडेक्स। |

**Returns:** float: The width of the column in points.

### उदाहरण

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

### संबंधित देखें
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
