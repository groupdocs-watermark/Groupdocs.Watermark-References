---
title: "Personalizar marcas de agua"
linkTitle: "Customize watermarks"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Ajusta la apariencia y posición de la marca de agua de texto o imagen — color, fuente, rotación, opacidad, tamaño y alineación — usando GroupDocs.Watermark para Python a través de .NET."
type: docs
url: /es/python-net/guides/customize/
is_root: false
weight: 60
---


GroupDocs.Watermark te permite controlar cómo se ve una marca de agua y dónde aparece. Ajusta el color, la fuente, la alineación, la rotación, la opacidad y el escalado para que coincidan con el estilo de tu documento.

## Customize text watermarks

Utiliza las propiedades de [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) como `foreground_color`, `opacity`, `rotate_angle`, `sizing_type`, `scale_factor`, `horizontal_alignment`, `vertical_alignment`, `x`, `y`, `width`, `height` y `consider_parent_margins`. El ejemplo a continuación escala una marca de agua \"DRAFT\" al tamaño de la página, la rota 45° y la hace semitransparente.

{{< tabs \"code-example-customize\">}}
{{< tab \"customize_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def customize_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("DRAFT", Font("Arial", 42.0))
        watermark.foreground_color = Color.dark_orange
        # Escala la marca de agua en relación a la página y gírala
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` es el archivo de ejemplo usado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Apply branded or legal disclaimers in a consistent style across pages (for example, "Confidential – Do Not Distribute").

## Customize image watermarks

Las marcas de agua de imagen admiten las mismas propiedades de posicionamiento, rotación y opacidad. Coloque un logotipo, sello o marca exactamente donde lo necesite:

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
{{< tab \"sample.pdf\" >}}

`sample.pdf` y `stamp.png` son los archivos de ejemplo usados en este ejemplo. Descargue [sample.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) y [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/stamp.png).

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 268 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_image_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}
