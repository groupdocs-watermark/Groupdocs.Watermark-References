---
title: SpreadsheetWatermarkHeaderFooterOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/
is_root: false
weight: 100
---


## SpreadsheetWatermarkHeaderFooterOptions class

Represents options when adding the watermark to a Spreadsheet header/footer.

Learn more:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

The SpreadsheetWatermarkHeaderFooterOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/__init__/) | Initializes a new instance of the SpreadsheetWatermarkHeaderFooterOptions class. |

### Properties
| Property | Description |
| :- | :- |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/worksheet_index/) | The index of the worksheet to add the watermark to. |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Gets the default value for the class. (inherited from [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls
import groupdocs.watermark.common as gwc

load_options = gw.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    watermark = gww.TextWatermark(
        "Test watermark",
        gww.Font("Segoe UI", 19.0, gww.FontStyle.BOLD)
    )
    watermark.foreground_color = gww.Color.red
    watermark.background_color = gww.Color.aqua
    watermark.vertical_alignment = gwc.VerticalAlignment.TOP
    watermark.horizontal_alignment = gwc.HorizontalAlignment.CENTER

    options = gwo_xls.SpreadsheetWatermarkHeaderFooterOptions()
    options.worksheet_index = 0

    watermarker.add(watermark, options)
    watermarker.save("spreadsheet.xlsx")
```

### See Also
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
