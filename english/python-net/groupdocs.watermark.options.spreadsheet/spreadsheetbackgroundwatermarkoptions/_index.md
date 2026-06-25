---
title: SpreadsheetBackgroundWatermarkOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
is_root: false
weight: 20
---


## SpreadsheetBackgroundWatermarkOptions class

Represents options when adding the watermark as a background to a Spreadsheet worksheet.

- Learn more: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

The SpreadsheetBackgroundWatermarkOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/__init__/) | Initializes a new instance of the SpreadsheetBackgroundWatermarkOptions class. |

### Properties
| Property | Description |
| :- | :- |
| [background_height](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_height/) | The desired height of the background image in pixels. |
| [background_width](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_width/) | The desired width of the background image in pixels. |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheet_index/) | The index of worksheet to add the watermark to. |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Gets the default value for the class. (inherited from [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls

load_options = gw.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    with gww.ImageWatermark("logo.gif") as watermark:
        options = gwo_xls.SpreadsheetBackgroundWatermarkOptions()
        watermarker.add(watermark, options)
    watermarker.save("spreadsheet.xlsx")
```

### See Also
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
