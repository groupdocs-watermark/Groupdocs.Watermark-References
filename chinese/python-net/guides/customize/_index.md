---
title: "自定义水印"
linkTitle: "Customize watermarks"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用通过 .NET 的 Python 版 GroupDocs.Watermark 调整文字或图像水印的外观和位置 — 颜色、字体、旋转、不透明度、尺寸和对齐方式 — 。"
type: docs
url: /zh/python-net/guides/customize/
is_root: false
weight: 60
---


GroupDocs.Watermark 让您控制水印的外观和出现位置。调整颜色、字体、对齐、旋转、不透明度和缩放，以匹配文档的样式。

## Customize text watermarks

使用 [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) 的属性，例如 `foreground_color`、`opacity`、`rotate_angle`、`sizing_type`、`scale_factor`、`horizontal_alignment`、`vertical_alignment`、`x`、`y`、`width`、`height` 和 `consider_parent_margins`。下面的示例将 "DRAFT" 水印按页面比例缩放，旋转 45°，并使其半透明。

{{< tabs "code-example-customize">}}
{{< tab "customize_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def customize_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("DRAFT", Font("Arial", 42.0))
        watermark.foreground_color = Color.dark_orange
        # 相对于页面缩放水印并旋转它
        watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS
        watermark.scale_factor = 0.7
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.5
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    customize_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` 是本示例使用的示例文件。点击 [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) 下载。

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Apply branded or legal disclaimers in a consistent style across pages (for example, "Confidential – Do Not Distribute").

## Customize image watermarks

图像水印支持相同的定位、旋转和不透明度属性。将徽标、印章或印记准确放置在所需位置：

{{< tabs "code-example-customize-image">}}
{{< tab "customize_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def customize_image_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        with ImageWatermark("./stamp.png") as watermark:
            watermark.horizontal_alignment = HorizontalAlignment.RIGHT
            watermark.vertical_alignment = VerticalAlignment.TOP
            watermark.rotate_angle = 15.0
            watermark.opacity = 0.8
            watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    customize_image_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` 和 `stamp.png` 是本示例使用的示例文件。下载 [sample.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) 和 [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/stamp.png)。

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 268 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_image_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}
