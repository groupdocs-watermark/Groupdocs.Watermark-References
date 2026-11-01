---
title: "Herhaalde watermerken toevoegen"
linkTitle: "Repeated watermarks"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Voeg herhaalde (getegelde) tekst‑ of afbeelding‑watermerken toe met tussenruimte, rotatie en patronen met behulp van GroupDocs.Watermark voor Python via .NET."
type: docs
url: /nl/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


Herhaalde (getegelde) watermerken laten u volledige pagina's bedekken met een patroon van tekst of afbeeldingen. U kunt de tussenruimte, rotatie, offsets regelen en verschillende tegel‑sjablonen kiezen door `tile_options` op het watermerk in te stellen.

## Add a repeated text watermark

Het voorbeeld hieronder tegelt een diagonale tekst‑watermerk over de hele pagina. De `line_spacing` en `watermark_spacing` worden uitgedrukt als een percentage van de pagina, en `tile_type` selecteert het tegel‑sjabloon.

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

        # Tussenruimte tussen regels en tussen herhaalde watermerken, uitgedrukt als een percentage van de pagina
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # Tegel het watermerk over de hele pagina
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

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

U kunt de [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) vervangen door een [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) om een logo of zegel over de pagina te tegelen op dezelfde manier — stel dezelfde `tile_options` in op het afbeelding‑watermerk.

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
