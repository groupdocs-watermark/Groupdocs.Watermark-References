---
title: "rasterize 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "将所有内容页转换为图像。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

将所有内容页转换为图像。

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| horizontal_resolution | `int` | 水平图像分辨率。 |
| vertical_resolution | `int` | 垂直图像分辨率。 |
| image_format | `PdfImageConversionFormat` | 图像格式。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # 添加水印（可选）
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # 以 100x100 DPI 对每页进行光栅化，生成 PNG 图像
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### 另请参见
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
