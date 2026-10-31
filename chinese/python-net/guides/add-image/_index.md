---
title: "添加图像水印"
linkTitle: "Add image watermarks"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "本文展示了如何向文档添加图像水印并通过 .NET 使用 GroupDocs.Watermark for Python 保存结果。"
type: docs
url: /zh/python-net/guides/add-image/
is_root: false
weight: 50
---


GroupDocs.Watermark 的主要功能之一是向文档添加图像水印。您可以从本地路径或流向文档或图像添加水印。有关完整的支持格式列表，请查看 [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/)。

## Add an image watermark

要添加图像水印，请按以下步骤操作：

1. 通过将文档路径（或流）传递给 [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) 类来打开文档。
2. 从水印图像文件（或流）创建一个 [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)。
3. 定位水印 — 例如，设置 `horizontal_alignment`、`vertical_alignment` 和 `opacity`。
4. 调用 `add()` 应用水印，调用 `save()` 写入结果。

{{< tabs "code-example-add-image">}}
{{< tab "add_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # 从徽标文件构建图像水印并将其居中
        watermark = ImageWatermark("./logo.png")
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.opacity = 0.7

        watermarker.add(watermark)
        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_image_watermark()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` 和 `logo.png` 是本示例使用的示例文件。下载 [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) 和 [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png)。

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

GroupDocs.Watermark 提供了更多图像水印功能 — 从流加载、缩放、平铺以及绝对或相对定位。请参阅高级指南中的 [Adding image watermarks](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/)。
