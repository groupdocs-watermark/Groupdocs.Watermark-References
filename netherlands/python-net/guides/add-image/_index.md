---
title: "Afbeeldingswatermerken toevoegen"
linkTitle: "Add image watermarks"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Dit artikel laat zien hoe je een afbeeldingswatermerk aan een document kunt toevoegen en het resultaat kunt opslaan met GroupDocs.Watermark voor Python via .NET."
type: docs
url: /nl/python-net/guides/add-image/
is_root: false
weight: 50
---


Een van de belangrijkste functies van GroupDocs.Watermark is het toevoegen van afbeeldingswatermerken aan documenten. Je kunt watermerken toevoegen aan documenten of afbeeldingen vanaf een lokaal pad, evenals vanaf een stream. Voor een volledige lijst met ondersteunde formaten, bekijk [Ondersteunde documentformaten](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add an image watermark

Om een afbeeldingswatermerk toe te voegen, volg deze stappen:

1. Open het document door het pad (of een stream) door te geven aan de [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) klasse.
2. Maak een [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) aan vanuit het watermerk‑afbeeldingsbestand (of een stream).
3. Positioneer het watermerk — bijvoorbeeld, stel `horizontal_alignment`, `vertical_alignment` en `opacity` in.
4. Roep `add()` aan om het watermerk toe te passen en `save()` om het resultaat op te slaan.

{{< tabs "code-example-add-image">}}
{{< tab "add_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # Maak een afbeeldingswatermerk van een logobestand en centreer het
        watermark = ImageWatermark("./logo.png")
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.opacity = 0.7

        watermarker.add(watermark)
        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_image_watermark()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` en `logo.png` zijn de voorbeeldbestanden die in dit voorbeeld worden gebruikt. Download [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) en [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

GroupDocs.Watermark biedt meer mogelijkheden voor afbeeldingswatermerken — laden vanuit streams, schalen, tegelen en absolute of relatieve positionering. Zie [Afbeeldingswatermerken toevoegen](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/) in de geavanceerde gids.
