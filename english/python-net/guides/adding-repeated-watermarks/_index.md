---
title: Adding repeated watermarks
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 210
---


## Repeated watermark

Repeated (tiled) watermarks let you cover entire pages with a pattern of text or images. You can control spacing, rotation, offsets, and choose different tiling templates.

### Text repeated watermark

Apply a text watermark across the whole page in a repeated pattern.

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww

with gw.Watermarker("sample.pdf") as watermarker:
    font = gww.Font("Arial", 19.0, gww.FontStyle.BOLD | gww.FontStyle.ITALIC)
    watermark = gww.TextWatermark("Watermark", font)
    watermark.foreground_color = gww.Color.red

    watermark.tile_options = gww.TileOptions()
    watermark.tile_options.line_spacing = gww.MeasureValue(gww.TileMeasureType.PERCENT, 12)
    watermark.tile_options.watermark_spacing = gww.MeasureValue(gww.TileMeasureType.PERCENT, 10)

    watermark.opacity = 0.2
    watermark.rotate_angle = -30

    watermarker.add(watermark)
    watermarker.save("result.pdf")
```

Rotate around the page origin instead of the center:

```python
watermark.tile_options.rotate_around_origin = True
```

Use offset/basket-weave and other templates:

```python
watermark.tile_options.tile_type = gww.TileType.OFFSET
# or
watermark.tile_options.tile_type = gww.TileType.BASKET_WEAVE
```

### Image repeated watermark

Apply a repeated image (such as a logo or seal) to cover the page.

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww

with gw.Watermarker("sample.pdf") as watermarker:
    watermark = gww.ImageWatermark("watermark.jpg")

    watermark.tile_options = gww.TileOptions()
    watermark.tile_options.line_spacing = gww.MeasureValue(gww.TileMeasureType.PERCENT, 12)
    watermark.tile_options.watermark_spacing = gww.MeasureValue(gww.TileMeasureType.PERCENT, 10)

    watermark.opacity = 0.3
    watermark.rotate_angle = -30

    watermarker.add(watermark)
    watermarker.save("result.pdf")
```
🔹 Use case: Protect sensitive PDFs by overlaying “Confidential” text across every page, or reinforce branding by repeating a logo in the background.
