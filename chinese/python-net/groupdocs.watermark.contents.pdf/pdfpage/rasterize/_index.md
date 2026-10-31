---
title: "rasterize 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "将页面内容转换为图像。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

将页面内容转换为图像。

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
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # 将第一页光栅化为 100 DPI 的 PNG 图像
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### 另请参见
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
