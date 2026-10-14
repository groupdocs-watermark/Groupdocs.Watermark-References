---
title: add_attachment method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Adds an attachment to the SpreadsheetWorksheet."
type: docs
url: /python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

Adds an attachment to the SpreadsheetWorksheet.

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_content | `list[int]` | bytes containing the content of the file to be attached. |
| source_full_name | `str` | str full name of the attached file (the extension is used to determine the appropriate application to open the file). |
| preview_image_content | `list[int]` | bytes preview image of the attached file as a byte array. |
| x | `float` | int x‑coordinate of the attachment frame (in points). |
| y | `float` | int y‑coordinate of the attachment frame (in points). |
| width | `float` | int width of the attachment frame (in points). |
| height | `float` | int height of the attachment frame (in points). |

**Returns:** None.

### Example

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

def add_attachment():
    with Watermarker("./sample.xlsx", SpreadsheetLoadOptions()) as watermarker:
        content = watermarker.get_content()
        with open("./sample.docx", "rb") as f:
            data = f.read()
        with open("./preview.png", "rb") as f:
            preview = f.read()
        # Embed the file in the first worksheet, shown as its preview image
        # at x=50, y=20 with a 100 x 120 frame
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### See Also
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
