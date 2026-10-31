---
title: "你好，世界！"
linkTitle: "Hello, World!"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "通过 .NET 为 Python 快速入门 GroupDocs.Watermark，只需创建并运行一个简单示例。"
type: docs
url: /zh/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
在探索通过 .NET 为 Python 的 GroupDocs.Watermark 时，"Hello, World!" 示例通常是第一步。它作为一个简单的测试，用于确认开发环境已正确设置且库能够如预期工作。

## Overview
通过 .NET 为 Python 的 GroupDocs.Watermark 允许您在各种文档格式中添加、搜索和移除水印。广泛的 [受支持的格式](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) 使其在不同用例中具有通用性。

## How to add a watermark
以下步骤演示如何使用通过 .NET 为 Python 的 GroupDocs.Watermark 向文档添加文本水印：

1. 导入所需的 `groupdocs.watermark` 类。
2. 使用指向示例文档的路径打开一个 [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)。
3. 使用所需的文本和字体创建一个 [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)，并设置样式。
4. 使用 `add()` 应用水印。
5. 保存结果。

## Complete example
下面的示例添加了一个半透明、对角线的 "Hello, Watermark!" 文本水印并保存结果：

{{< tabs "code-example-hello-world" >}}
{{< tab "hello_world.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # 打开文档，添加单个文本水印，并保存结果。
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("Hello, Watermark!", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermark.rotate_angle = 45.0
        watermarker.add(watermark)
        watermarker.save("./output.pdf")

    print("Watermark added successfully. Output saved to ./output.pdf.")

if __name__ == "__main__":
    hello_world()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` 是本示例中使用的示例文件。点击 [此处](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf) 下载它。

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

水印会保存回与 `output.pdf` 相同的 PDF 格式。要在不同的文档上添加水印，请更改输入路径和输出扩展名 —— GroupDocs.Watermark 会以输入文档的格式保存。

## Additional resources
此演示引用了 GroupDocs.Watermark for Python via .NET 的 [代码示例](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/)。
