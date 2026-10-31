---
title: "Hinzufügen wiederholter Wasserzeichen"
linkTitle: "Repeated watermarks"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Fügen Sie wiederholte (gekachelte) Text- oder Bildwasserzeichen mit Abstand, Drehung und Mustern mithilfe von GroupDocs.Watermark für Python über .NET hinzu."
type: docs
url: /de/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


Wiederholte (gekachelte) Wasserzeichen ermöglichen es, ganze Seiten mit einem Muster aus Text oder Bildern zu bedecken. Sie können Abstand, Drehung, Versätze steuern und verschiedene Kachelvorlagen auswählen, indem Sie `tile_options` am Wasserzeichen setzen.

## Add a repeated text watermark

Das nachstehende Beispiel kachelt ein diagonales Textwasserzeichen über die gesamte Seite. Die `line_spacing` und `watermark_spacing` werden als Prozentsatz der Seite angegeben, und `tile_type` wählt die Kachelvorlage aus.

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

        # Abstand zwischen Zeilen und zwischen wiederholten Wasserzeichen, als Prozentsatz der Seite
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # Kacheln Sie das Wasserzeichen über die gesamte Seite
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

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf), um sie herunterzuladen.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Sie können das [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) durch ein [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) ersetzen, um ein Logo oder Siegel über die Seite zu kacheln – setzen Sie dieselben `tile_options` auf das Bildwasserzeichen.

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
