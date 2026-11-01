---
title: "Anpassa vattenmärken"
linkTitle: "Customize watermarks"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Justera text‑ eller bildvattenstämpelns utseende och position — färg, typsnitt, rotation, opacitet, storlek och justering — med GroupDocs.Watermark för Python via .NET."
type: docs
url: /sv/python-net/guides/customize/
is_root: false
weight: 60
---


GroupDocs.Watermark låter dig styra hur en vattenstämpel ser ut och var den visas. Justera färg, typsnitt, justering, rotation, opacitet och skalning för att matcha ditt dokuments stil.

## Customize text watermarks

Använd egenskaperna för [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) såsom `foreground_color`, `opacity`, `rotate_angle`, `sizing_type`, `scale_factor`, `horizontal_alignment`, `vertical_alignment`, `x`, `y`, `width`, `height` och `consider_parent_margins`. Exemplet nedan skalar en \"DRAFT\"‑vattenstämpel till sidan, roterar den 45° och gör den halvtransparent.

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
        # Skala vattenstämpeln relativt sidan och rotera den
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

`sample.pdf` är exempel‑filen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) för att ladda ner den.

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

Bildvattenmärken stöder samma positionerings‑, rotations‑ och opacitets‑egenskaper. Placera en logotyp, stämpel eller sigill exakt där du behöver det:

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

`sample.pdf` och `stamp.png` är exempelfilerna som används i detta exempel. Ladda ner [sample.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) och [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/stamp.png).

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 268 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_image_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}
