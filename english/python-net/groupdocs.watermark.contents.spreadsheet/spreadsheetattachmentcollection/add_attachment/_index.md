---
title: add_attachment method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
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
| file_content | `list[int]` | The content of the file to be attached. |
| source_full_name | `str` | The full name of the attached file. The extension is used to determine the appropriate application to open the file. |
| preview_image_content | `list[int]` | The attached file preview image as a byte array. |
| x | `float` | The x-coordinate of the attachment frame (in points). |
| y | `float` | The y-coordinate of the attachment frame (in points). |
| width | `float` | The width of the attachment frame in points. |
| height | `float` | The height of the attachment frame in points. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.spreadsheet as gwc_xls

load_options = gw.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    content = watermarker.get_content(gwc_xls.SpreadsheetContent)
    worksheet = content.worksheets[0]
    with open("document.docx", "rb") as f_doc, open("document_preview.png", "rb") as f_prev:
        worksheet.attachments.add_attachment(
            f_doc.read(),
            "sample document.docx",
            f_prev.read(),
            50,
            100,
            200,
            400,
        )
    watermarker.save("spreadsheet.xlsx")
```

### See Also
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
