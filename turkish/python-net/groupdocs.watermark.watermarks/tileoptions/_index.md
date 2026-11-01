---
title: "TileOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Döşeme modunda filigranları yapılandırma seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.watermarks/tileoptions/
is_root: false
weight: 140
---


## TileOptions class

Döşeme modunda filigranları yapılandırma seçeneklerini temsil eder.

TileOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/__init__/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [line_spacing](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/line_spacing/) | Döşeme modundaki filigranlar için satırlar arasındaki boşluk. |
| [rotate_around_origin](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/rotate_around_origin/) | Bu özellik, yinelenen filigranların belgenin merkezinde döndürülüp döndürülmediğini gösterir. |
| [tile_type](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/tile_type/) | Filigranlar için döşeme hizalama türü. |
| [watermark_spacing](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/watermark_spacing/) | Döşeme modundaki filigranlar için seriler arasındaki boşluk. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import (
    TextWatermark, Font, Color, TextAlignment,
    TileOptions, TileType, MeasureValue, TileMeasureType,
)

with Watermarker("./sample.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
    watermark.foreground_color = Color.gray
    watermark.opacity = 0.3
    watermark.rotate_angle = -45.0
    watermark.text_alignment = TextAlignment.CENTER

    line_spacing = MeasureValue()
    line_spacing.measure_type = TileMeasureType.PERCENT
    line_spacing.value = 12.0

    watermark_spacing = MeasureValue()
    watermark_spacing.measure_type = TileMeasureType.PERCENT
    watermark_spacing.value = 10.0

    tile_options = TileOptions()
    tile_options.tile_type = TileType.ONE_THIRD_OFFSET
    tile_options.line_spacing = line_spacing
    tile_options.watermark_spacing = watermark_spacing
    watermark.tile_options = tile_options

    watermarker.add(watermark)
```

### Guides
`TileOptions` kullanan görev kılavuzları:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Ayrıca Bakınız
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
