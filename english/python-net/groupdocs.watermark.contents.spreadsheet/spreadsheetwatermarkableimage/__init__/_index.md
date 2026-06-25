---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Initializes a new SpreadsheetWatermarkableImage instance using the provided image data.

```python
def __init__(self, image_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| image_data | `list[int]` | The array of unsigned bytes from which to create the SpreadsheetWatermarkableImage. |

### Example

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### See Also
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
