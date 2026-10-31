---
title: "Attachment 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示附加到文档的文件。"
type: docs
url: /zh/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

表示附加到文档的文件。

了解更多

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

Attachment 类型公开以下成员:

### 方法
| 方法 | 描述 |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | 从附件文件加载内容。 |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | 使用指定的加载选项从附件文件加载内容。 |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | 使用指定的加载选项和设置从附件文件加载内容。 |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | 检索存储在附件文件中的文档信息。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | 附件文件内容。 |

### 示例

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.pdf import PdfLoadOptions
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww
from groupdocs.watermark.common import FileType

watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))
load_options = PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    pdf_content = watermarker.get_content()
    for attachment in pdf_content.attachments:
        info = attachment.get_document_info()
        if info.file_type != FileType.UNKNOWN and not info.is_encrypted:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    watermarker.save("output.pdf")
```

### 另请参见
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
