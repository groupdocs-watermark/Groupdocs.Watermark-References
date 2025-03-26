---
title: add_link method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 30
---

## add_link {#str-bytes-float-float-float-float}

Adds an attachment by a link (the document will not contain attached file content).



```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_full_name | str | The linked file path. |
| preview_image_content | bytes | The attached file preview image as a byte array. |
| x | float | The x-coordinate of the attachment frame (in points). |
| y | float | The y-coordinate of the attachment frame (in points). |
| width | float | The width of the attachment frame in points. |
| height | float | The height of the attachment frame in points. |



### See Also
* module [`groupdocs.watermark.contents.spreadsheet`](../../)
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection)
