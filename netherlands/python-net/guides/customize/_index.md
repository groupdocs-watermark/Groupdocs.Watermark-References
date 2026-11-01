---
title: "Watermerken aanpassen"
linkTitle: "Customize watermarks"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Pas het uiterlijk en de positie van tekst- of afbeeldingswatermerken aan — kleur, lettertype, rotatie, doorzichtigheid, grootte en uitlijning — met GroupDocs.Watermark voor Python via .NET."
type: docs
url: /nl/python-net/guides/customize/
is_root: false
weight: 60
---


GroupDocs.Watermark stelt je in staat te bepalen hoe een watermerk eruitziet en waar het verschijnt. Pas kleur, lettertype, uitlijning, rotatie, doorzichtigheid en schaal aan om overeen te komen met de stijl van je document.

## Customize text watermarks

Gebruik de eigenschappen van [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) zoals `foreground_color`, `opacity`, `rotate_angle`, `sizing_type`, `scale_factor`, `horizontal_alignment`, `vertical_alignment`, `x`, `y`, `width`, `height` en `consider_parent_margins`. Het onderstaande voorbeeld schaalt een "DRAFT" watermerk naar de pagina, roteert het 45° en maakt het halfdoorzichtig.

{{< tabs "code-example-customize">}}
{{< tab "customize_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def customize_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("DRAFT", Font("Arial", 42.0))
        watermark.foreground_color = Color.dark_orange
        # Schaal het watermerk relatief ten opzichte van de pagina en roteer het
        watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS
        watermark.scale_factor = 0.7
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.5
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    customize_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Apply branded or legal disclaimers in a consistent style across pages (for example, "Confidential – Do Not Distribute").

## Customize image watermarks

Afbeeldingswatermerken ondersteunen dezelfde positionerings-, rotatie- en doorzichtigheids‑eigenschappen. Plaats een logo, stempel of zegel precies waar je het nodig hebt:

{{< tabs "code-example-customize-image">}}
{{< tab "customize_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def customize_image_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        with ImageWatermark("./stamp.png") as watermark:
            watermark.horizontal_alignment = HorizontalAlignment.RIGHT
            watermark.vertical_alignment = VerticalAlignment.TOP
            watermark.rotate_angle = 15.0
            watermark.opacity = 0.8
            watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    customize_image_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` en `stamp.png` zijn de voorbeeldbestanden die in dit voorbeeld worden gebruikt. Download [sample.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) en [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/stamp.png).

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 268 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_image_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}
