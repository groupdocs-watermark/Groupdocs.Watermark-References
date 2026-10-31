---
title: "Wasserzeichen anpassen"
linkTitle: "Customize watermarks"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Passen Sie das Aussehen und die Position von Text‑ oder Bildwasserzeichen an – Farbe, Schriftart, Drehung, Transparenz, Größe und Ausrichtung – mithilfe von GroupDocs.Watermark für Python über .NET."
type: docs
url: /de/python-net/guides/customize/
is_root: false
weight: 60
---


GroupDocs.Watermark ermöglicht es Ihnen, das Aussehen und die Platzierung eines Wasserzeichens zu steuern. Passen Sie Farbe, Schriftart, Ausrichtung, Drehung, Transparenz und Skalierung an, um den Stil Ihres Dokuments zu entsprechen.

## Customize text watermarks

Verwenden Sie die Eigenschaften von [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) wie `foreground_color`, `opacity`, `rotate_angle`, `sizing_type`, `scale_factor`, `horizontal_alignment`, `vertical_alignment`, `x`, `y`, `width`, `height` und `consider_parent_margins`. Das nachstehende Beispiel skaliert ein „DRAFT“-Wasserzeichen auf die Seite, dreht es um 45° und macht es halbtransparent.

{{< tabs "code-example-customize">}}
{{< tab \"customize_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def customize_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("DRAFT", Font("Arial", 42.0))
        watermark.foreground_color = Color.dark_orange
        # Skaliere das Wasserzeichen relativ zur Seite und rotiere es
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

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicke [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) zum Herunterladen.

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

Bildwasserzeichen unterstützen dieselben Positionierungs-, Rotations- und Transparenzeigenschaften. Platziere ein Logo, einen Stempel oder ein Siegel genau dort, wo du es benötigst:

{{< tabs \"code-example-customize-image\" >}}
{{< tab \"customize_image_watermark.py\" >}}
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

`sample.pdf` und `stamp.png` sind die Beispieldateien, die in diesem Beispiel verwendet werden. Lade [sample.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) und [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/stamp.png) herunter.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 268 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_image_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}
