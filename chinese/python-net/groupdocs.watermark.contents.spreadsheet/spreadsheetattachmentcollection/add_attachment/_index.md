---
title: "add_attachment 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "向 SpreadsheetWorksheet 添加附件。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

向 SpreadsheetWorksheet 添加附件。

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_content | `list[int]` | 包含要附加的文件内容的字节。 |
| source_full_name | `str` | str 附加文件的完整名称（扩展名用于确定打开文件的适当应用程序）。 |
| preview_image_content | `list[int]` | bytes 附加文件的预览图像（字节数组）。 |
| x | `float` | int 附件框架的 x 坐标（单位为点）。 |
| y | `float` | int 附件框架的 y 坐标（单位为点）。 |
| width | `float` | int 附件框架的宽度（单位为点）。 |
| height | `float` | int 附件框架的高度（单位为点）。 |

**Returns:** None.

### 示例

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
        # 将文件嵌入到第一个工作表中，以其预览图像显示
        # 在 x=50, y=20 处，使用 100 x 120 的框架
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### 另请参见
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
