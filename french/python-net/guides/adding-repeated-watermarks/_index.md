---
title: "Ajout de filigranes répétés"
linkTitle: "Repeated watermarks"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Ajoutez des filigranes texte ou image répétés (en mosaïque) avec espacement, rotation et motifs en utilisant GroupDocs.Watermark pour Python via .NET."
type: docs
url: /fr/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


Les filigranes répétés (en mosaïque) vous permettent de couvrir des pages entières avec un motif de texte ou d’images. Vous pouvez contrôler l’espacement, la rotation, les décalages et choisir différents modèles de mosaïque en définissant `tile_options` sur le filigrane.

## Add a repeated text watermark

L’exemple ci‑dessous applique en mosaïque un filigrane texte diagonal sur toute la page. Les paramètres `line_spacing` et `watermark_spacing` sont exprimés en pourcentage de la page, et `tile_type` sélectionne le modèle de mosaïque.

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

        # Espacement entre les lignes et entre les filigranes répétés, exprimé en pourcentage de la page
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # Appliquer le filigrane en mosaïque sur toute la page
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

`sample.pdf` est le fichier d’exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Vous pouvez remplacer le [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) par un [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) pour appliquer en mosaïque un logo ou un sceau sur la page de la même manière — définissez les mêmes `tile_options` sur le filigrane image.

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
