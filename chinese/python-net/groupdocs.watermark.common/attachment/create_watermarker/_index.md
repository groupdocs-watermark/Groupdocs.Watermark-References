---
title: "create_watermarker 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "从附件文件加载内容。"
type: docs
url: /zh/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

从附件文件加载内容。

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### 示例

```python
    import groupdocs.watermark as gw
    import groupdocs.watermark.contents.pdf as gwc_pdf
    import groupdocs.watermark.watermarks as gww

    watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))

    with gw.Watermarker("document.pdf") as watermarker:
        pdf_content = watermarker.get_content()
        for attachment in pdf_content.attachments:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    ```

## create_watermarker {#load_options}

使用指定的加载选项从附件文件加载内容。

```python
def create_watermarker(self, load_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| load_options | `LoadOptions` | 加载附件内容时使用的附加选项。 |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

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

## create_watermarker {#load_options-watermarker_settings}

使用指定的加载选项和设置从附件文件加载内容。

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| load_options | `LoadOptions` | 加载附件内容时使用的附加选项。 |
| watermarker_settings | `WatermarkerSettings` | 处理已加载文档时使用的附加设置。 |

**Returns:** The instance of appropriate descendant of `Content` class.

### 示例

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww

watermark = gww.TextWatermark("Sample watermark", gww.Font("Arial", 19.0))

with gw.Watermarker("document.pdf") as watermarker:
    pdf_content = watermarker.get_content()
    for attachment in pdf_content.attachments:
        with attachment.create_watermarker() as attached:
            attached.add(watermark)
            attached.save()
    watermarker.save("output.pdf")
```

### 另请参见
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
