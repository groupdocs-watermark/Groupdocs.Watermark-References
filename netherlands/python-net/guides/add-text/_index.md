---
title: "Tekstwatermerken toevoegen"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Dit artikel laat zien hoe je een tekstwatermerk aan een document toevoegt en het resultaat opslaat met GroupDocs.Watermark voor Python via .NET."
type: docs
url: /nl/python-net/guides/add-text/
is_root: false
weight: 40
---


Een van de belangrijkste functies van GroupDocs.Watermark is het toevoegen van tekstwatermerken aan documenten. Je kunt watermerken toevoegen aan documenten of afbeeldingen vanaf een lokaal pad, evenals vanaf een stroom. Voor een volledige lijst van ondersteunde formaten, bekijk [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add a text watermark

Volg deze stappen om een tekstwatermerk toe te voegen:

1. Open het document door het pad (of een stroom) door te geven aan de [Watermarker](https://reference.groupdocs.com/watermark/python-net/) klasse, gebruik een `with`‑blok zodat het document automatisch wordt vrijgegeven.
2. Maak een [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) aan met de gewenste tekst en een [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/).
3. Style het watermerk — bijvoorbeeld, stel `foreground_color` en uitlijning in.
4. Roep `add()` aan om het watermerk toe te passen en `save()` om het resultaat op te slaan.

{{< tabs \"code-example-add-text\">}}
{{< tab \"add_text_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # Bouw het tekstwatermerk en style het
        watermark = TextWatermark("Top Secret", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.4

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Voer het programma uit. Een nieuw watergemarkeerd document verschijnt op het opgegeven pad.

## What's next

GroupDocs.Watermark biedt nog veel meer mogelijkheden voor tekstwatermerken — achtergrond- en voorgrondkleuren, aangepaste lettertypen, doorzichtigheid, rotatie, tegelpatroon, en absolute of relatieve positionering. Zie [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/) in de geavanceerde gids.
