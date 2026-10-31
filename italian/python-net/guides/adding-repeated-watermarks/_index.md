---
title: "Aggiunta di filigrane ripetute"
linkTitle: "Repeated watermarks"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Aggiungi filigrane di testo o immagine ripetute (a tasselli) con spaziatura, rotazione e modelli usando GroupDocs.Watermark per Python tramite .NET."
type: docs
url: /it/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


Le filigrane ripetute (a tasselli) ti consentono di coprire intere pagine con un motivo di testo o immagini. Puoi controllare la spaziatura, la rotazione, gli offset e scegliere diversi modelli di tassellatura impostando `tile_options` sulla filigrana.

## Add a repeated text watermark

L'esempio seguente dispone una filigrana di testo diagonale su tutta la pagina. `line_spacing` e `watermark_spacing` sono espressi come percentuale della pagina, e `tile_type` seleziona il modello di tassellatura.

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

        # Spaziatura tra le linee e tra le filigrane ripetute, espressa in percentuale della pagina
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # Distribuisci la filigrana su tutta la pagina
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

`sample.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Puoi sostituire il [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) con un [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) per distribuire un logo o un sigillo su tutta la pagina nello stesso modo — imposta le stesse `tile_options` sulla filigrana immagine.

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
