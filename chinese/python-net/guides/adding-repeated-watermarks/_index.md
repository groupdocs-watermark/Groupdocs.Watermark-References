---
title: "添加重复水印"
linkTitle: "Repeated watermarks"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用 GroupDocs.Watermark for Python via .NET 添加重复（平铺）文本或图像水印，可设置间距、旋转和图案。"
type: docs
url: /zh/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


重复（平铺）水印可让您使用文本或图像的图案覆盖整页。您可以通过在水印上设置 `tile_options` 来控制间距、旋转、偏移，并选择不同的平铺模板。

## Add a repeated text watermark

下面的示例将对角线文本水印平铺到整页。`line_spacing` 和 `watermark_spacing` 以页面的百分比表示，`tile_type` 用于选择平铺模板。

{{< tabs "code-example-adding-repeated-watermarks">}}
{{< tab "add_repeated_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import (
    TextWatermark, Font, Color, TextAlignment,
    TileOptions, TileType, MeasureValue, TileMeasureType,
)

def add_repeated_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.gray
        watermark.opacity = 0.3
        watermark.rotate_angle = -45.0
        watermark.text_alignment = TextAlignment.CENTER

        # 行间距和重复水印之间的间距，以页面的百分比表示
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # 将水印平铺到整页
        tile_options = TileOptions()
        tile_options.tile_type = TileType.ONE_THIRD_OFFSET
        tile_options.line_spacing = line_spacing
        tile_options.watermark_spacing = watermark_spacing
        watermark.tile_options = tile_options

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_repeated_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` 是本示例使用的示例文件。点击[此处](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf)下载。

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

您可以将[`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)替换为[`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)，以相同方式将徽标或印章平铺到整页——在图像水印上设置相同的 `tile_options`。

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
