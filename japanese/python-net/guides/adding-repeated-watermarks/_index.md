---
title: "繰り返し透かしの追加"
linkTitle: "Repeated watermarks"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "GroupDocs.Watermark for Python via .NET を使用して、間隔、回転、パターンを設定した繰り返し（タイル状）のテキストまたは画像の透かしを追加します。"
type: docs
url: /ja/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


繰り返し（タイル状）の透かしを使用すると、テキストや画像のパターンでページ全体を覆うことができます。`tile_options` を設定することで、間隔、回転、オフセットを制御し、さまざまなタイルテンプレートを選択できます。

## Add a repeated text watermark

以下の例では、対角線上のテキスト透かしをページ全体にタイル状に配置します。`line_spacing` と `watermark_spacing` はページのパーセンテージで表され、`tile_type` がタイルテンプレートを選択します。

{{< tabs \"code-example-adding-repeated-watermarks\">}}
{{< tab \"add_repeated_watermark.py\" >}}
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

        # 行間および繰り返し透かし間の間隔（ページのパーセンテージ）
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # 透かしをページ全体にタイル状に配置する
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

同じ方法でページ全体にロゴやシールをタイル状に配置するには、[`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) を [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) に置き換えることができます。画像透かしにも同じ `tile_options` を設定してください。

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
