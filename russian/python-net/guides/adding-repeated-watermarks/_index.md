---
title: "Добавление повторяющихся водяных знаков"
linkTitle: "Repeated watermarks"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Добавьте повторяющиеся (мозаичные) текстовые или графические водяные знаки с интервалом, вращением и шаблонами, используя GroupDocs.Watermark для Python через .NET."
type: docs
url: /ru/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


Повторяющиеся (мозаичные) водяные знаки позволяют покрыть целые страницы шаблоном текста или изображений. Вы можете управлять интервалом, вращением, смещениями и выбирать различные шаблоны мозаики, задавая `tile_options` для водяного знака.

## Add a repeated text watermark

Пример ниже размещает диагональный текстовый водяной знак по всей странице. Параметры `line_spacing` и `watermark_spacing` задаются в процентах от страницы, а `tile_type` выбирает шаблон мозаики.

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

        # Интервал между строками и между повторяющимися водяными знаками, в процентах от страницы
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # Разместите водяной знак по всей странице
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

`sample.pdf` — пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Вы можете заменить [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) на [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/), чтобы разместить логотип или печать по всей странице тем же способом — задайте те же `tile_options` для графического водяного знака.

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
