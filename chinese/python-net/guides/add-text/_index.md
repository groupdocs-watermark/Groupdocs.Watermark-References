---
title: "添加文字水印"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "本文展示了如何使用 GroupDocs.Watermark for Python via .NET 为文档添加文字水印并保存结果。"
type: docs
url: /zh/python-net/guides/add-text/
is_root: false
weight: 40
---


GroupDocs.Watermark 的主要功能之一是向文档添加文本水印。您可以从本地路径或流向文档或图像添加水印。有关受支持格式的完整列表，请查看 [受支持的文档格式](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/)。

## Add a text watermark

要添加文本水印，请按照以下步骤操作：

1. 通过将文档路径（或流）传递给 [Watermarker](https://reference.groupdocs.com/watermark/python-net/) 类来打开文档，使用 `with` 块以便文档自动释放。
2. 使用所需的文本和 [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/) 创建一个 [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)。
3. 为水印设置样式——例如，设置 `foreground_color` 和对齐方式。
4. 调用 `add()` 应用水印，调用 `save()` 写入结果。

{{< tabs "code-example-add-text">}}
{{< tab "add_text_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # 构建文本水印并设置样式
        watermark = TextWatermark("Top Secret", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.4

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` 是本示例使用的示例文件。点击 [此处](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) 下载。

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

运行程序。一个新的带水印的文档会出现在指定路径。

## What's next

GroupDocs.Watermark 提供了更多文本水印功能——背景色和前景色、自定义字体、不透明度、旋转、平铺以及绝对或相对定位。请参阅高级指南中的 [添加文本水印](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/)。
