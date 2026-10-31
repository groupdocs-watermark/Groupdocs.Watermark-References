---
title: "PreviewOptions 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "提供用于设置预览生成的要求和流委托的选项。"
type: docs
url: /zh/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

提供用于设置预览生成的要求和流委托的选项。

该 PreviewOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | 初始化一个在使用后关闭输出流的 PreviewOptions 实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | 初始化一个将输出流返回给客户端以供进一步使用的 PreviewOptions 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | 用于获取每个渲染页面的可写流的页面流创建委托。 |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | 页面预览高度。 |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | 用于生成预览的页码数组。 |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | 预览图像格式。 |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | 页面预览完成委托。 |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | 页面预览宽度。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # 为每个要渲染的页面提供可写文件流
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### Guides
使用 `PreviewOptions` 的任务指南：

* [Document preview](/watermark/python-net/guides/preview/)

### 另请参见
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
