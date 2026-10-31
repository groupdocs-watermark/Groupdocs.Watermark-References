---
title: "Menambahkan watermark berulang"
linkTitle: "Repeated watermarks"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Tambahkan watermark teks atau gambar berulang (berubin) dengan jarak, rotasi, dan pola menggunakan GroupDocs.Watermark untuk Python via .NET."
type: docs
url: /id/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


Watermark berulang (berubin) memungkinkan Anda menutupi seluruh halaman dengan pola teks atau gambar. Anda dapat mengontrol jarak, rotasi, offset, dan memilih templat ubin yang berbeda dengan mengatur `tile_options` pada watermark.

## Add a repeated text watermark

Contoh di bawah ini menaruh watermark teks diagonal di seluruh halaman. `line_spacing` dan `watermark_spacing` dinyatakan sebagai persentase halaman, dan `tile_type` memilih templat ubin.

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

        # Jarak antar baris dan antar watermark berulang, sebagai persentase halaman
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # Letakkan watermark di seluruh halaman
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

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Anda dapat mengganti [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) dengan [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) untuk menaruh logo atau segel di seluruh halaman dengan cara yang sama — atur `tile_options` yang sama pada watermark gambar.

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
