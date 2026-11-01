---
title: "Agregar marcas de agua repetidas"
linkTitle: "Repeated watermarks"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Agregue marcas de agua de texto o imagen repetidas (en mosaico) con espaciado, rotación y patrones usando GroupDocs.Watermark para Python a través de .NET."
type: docs
url: /es/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


Las marcas de agua repetidas (en mosaico) le permiten cubrir páginas completas con un patrón de texto o imágenes. Puede controlar el espaciado, la rotación, los desplazamientos y elegir diferentes plantillas de mosaico configurando `tile_options` en la marca de agua.

## Add a repeated text watermark

El ejemplo a continuación coloca en mosaico una marca de agua de texto diagonal en toda la página. Los parámetros `line_spacing` y `watermark_spacing` se expresan como un porcentaje de la página, y `tile_type` selecciona la plantilla de mosaico.

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

        # Espaciado entre líneas y entre marcas de agua repetidas, como porcentaje de la página
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # Coloque en mosaico la marca de agua en toda la página
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

`sample.pdf` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Puede reemplazar el [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) con un [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) para colocar en mosaico un logotipo o sello en toda la página de la misma manera — configure los mismos `tile_options` en la marca de agua de imagen.

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
