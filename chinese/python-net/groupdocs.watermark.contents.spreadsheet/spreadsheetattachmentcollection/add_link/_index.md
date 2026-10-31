---
title: "add_link 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "通过链接添加附件（文档将不包含附件文件内容）。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

通过链接添加附件（文档将不包含附件文件内容）。

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_full_name | `str` | 链接文件路径。 |
| preview_image_content | `list[int]` | 附件文件的预览图像，以字节数组形式。 |
| x | `float` | 附件框架的 x 坐标（单位：点）。 |
| y | `float` | 附件框架的 y 坐标（单位：点）。 |
| width | `float` | 附件框架的宽度（单位：点）。 |
| height | `float` | 附件框架的高度（以磅为单位）。 |

### 示例

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions
import groupdocs.watermark.contents.spreadsheet as gwc_xls

load_options = SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    content = watermarker.get_content()
    worksheet = content.worksheets[0]
    with open("document_preview.png", "rb") as f_prev:
        worksheet.attachments.add_link(
            "document.docx",
            f_prev.read(),
            50,
            100,
            200,
            400,
        )
    watermarker.save("output.xlsx")
```

### 另请参见
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
