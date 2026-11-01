---
title: "Tekrarlanan filigranları ekleme"
linkTitle: "Repeated watermarks"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "GroupDocs.Watermark for Python via .NET kullanarak aralık, döndürme ve desenlerle tekrarlanan (döşeli) metin veya görüntü filigranları ekleyin."
type: docs
url: /tr/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


Tekrarlanan (döşeli) filigranlar, metin veya görüntü desenleriyle tüm sayfaları kaplamanızı sağlar. `tile_options` ayarını filigrana belirleyerek aralık, döndürme, ofsetleri kontrol edebilir ve farklı döşeme şablonlarını seçebilirsiniz.

## Add a repeated text watermark

Aşağıdaki örnek, sayfanın tamamına çapraz bir metin filigranı döşer. `line_spacing` ve `watermark_spacing` sayfanın yüzdesi olarak ifade edilir ve `tile_type` döşeme şablonunu seçer.

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

        # Satırlar ve tekrarlanan filigranlar arasındaki boşluk, sayfanın yüzdesi olarak
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # Filigranı tüm sayfaya döşe
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

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Aynı şekilde sayfaya bir logo veya mühür döşemek için [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) yerine bir [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) kullanabilirsiniz — görüntü filigranında aynı `tile_options` ayarını yapın.

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
