---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "初始化一个使用指定图像数据的 PdfWatermarkableImage 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

使用指定的图像数据初始化 [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) 类的新实例。

```python
def __init__(self, image_data):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_data | `list[int]` | 用于创建 `PdfWatermarkableImage` 的无符号字节数组。 |

### 示例

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### 另请参见
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
