---
title: "فئة TileOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل خيارات تكوين العلامات المائية في وضع البلاط."
type: docs
url: /ar/python-net/groupdocs.watermark.watermarks/tileoptions/
is_root: false
weight: 140
---


## TileOptions class

يمثل خيارات تكوين العلامات المائية في وضع البلاط.

يعرض نوع TileOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/__init__/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [line_spacing](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/line_spacing/) | التباعد بين السطور للعلامات المائية في وضع البلاط. |
| [rotate_around_origin](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/rotate_around_origin/) | تشير الخاصية إلى ما إذا كانت العلامات المائية المتكررة تدور حول مركز المستند. |
| [tile_type](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/tile_type/) | نوع محاذاة البلاط للعلامات المائية. |
| [watermark_spacing](/watermark/python-net/groupdocs.watermark.watermarks/tileoptions/watermark_spacing/) | التباعد بين المتسلسلات للعلامات المائية في وضع البلاط. |

### مثال

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
أدلة المهام التي تستخدم `TileOptions`:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### انظر أيضًا
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
