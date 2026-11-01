---
title: "Lägga till upprepade vattenstämplar"
linkTitle: "Repeated watermarks"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Lägg till upprepade (plattade) text- eller bildvattenstämplar med avstånd, rotation och mönster med hjälp av GroupDocs.Watermark för Python via .NET."
type: docs
url: /sv/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


Upprepade (plattade) vattenstämplar låter dig täcka hela sidor med ett mönster av text eller bilder. Du kan kontrollera avstånd, rotation, förskjutningar och välja olika plattningsmallar genom att ställa in `tile_options` på vattenstämpeln.

## Add a repeated text watermark

Exemplet nedan plattar en diagonal textvattenstämpel över hela sidan. `line_spacing` och `watermark_spacing` uttrycks som en procentandel av sidan, och `tile_type` väljer plattningsmallen.

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

        # Avstånd mellan rader och mellan upprepade vattenstämplar, som en procentandel av sidan
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # Platta vattenstämpeln över hela sidan
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

`sample.pdf` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Du kan ersätta [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) med en [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) för att platta en logotyp eller sigill över sidan på samma sätt — ställ in samma `tile_options` på bildvattenstämpeln.

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
