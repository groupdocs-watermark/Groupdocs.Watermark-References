---
title: add_attachment method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 20
---

## add_attachment {#bytes-str-bytes-float-float-float-float}

Adds an attachment to the [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet).



```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_content | bytes | The content of the file to be attached. |
| source_full_name | str | The full name of the attached file (The extension is used to<br/>determine appropriate application to open the file). |
| preview_image_content | bytes | The attached file preview image as a byte array. |
| x | float | The x-coordinate of the attachment frame (in points). |
| y | float | The y-coordinate of the attachment frame (in points). |
| width | float | The width of the attachment frame in points. |
| height | float | The height of the attachment frame in points. |



### See Also
* module [`groupdocs.watermark.contents.spreadsheet`](../../)
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection)
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet)
