---
title: "PdfArtifactWatermarkOptions 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示在向 PDF 文档添加工件水印时的水印添加选项。"
type: docs
url: /zh/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
is_root: false
weight: 20
---


## PdfArtifactWatermarkOptions class

表示在向 PDF 文档添加工件水印时的水印添加选项。

了解更多：
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

PdfArtifactWatermarkOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/__init__/) | 初始化 [`PdfArtifactWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/) 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/page_index/) | 用于添加水印的页索引。 |

### 字段
| 字段 | 描述 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | 获取类的默认值。（继承自 [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)） |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfArtifactWatermarkOptions

with Watermarker("./test.pdf", PdfLoadOptions()) as watermarker:
    with ImageWatermark("./icon.png") as watermark:
        watermark.horizontal_alignment = HorizontalAlignment.RIGHT
        watermark.vertical_alignment = VerticalAlignment.BOTTOM
        options = PdfArtifactWatermarkOptions()
        options.page_index = -1  # default: all pages
        watermarker.add(watermark, options)
        watermarker.save()
```

### 另请参见
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
