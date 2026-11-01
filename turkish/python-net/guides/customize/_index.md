---
title: "Filigranları özelleştirin"
linkTitle: "Customize watermarks"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "GroupDocs.Watermark for Python via .NET kullanarak metin veya görüntü filigranının görünümünü ve konumunu — renk, yazı tipi, dönüş, opaklık, boyutlandırma ve hizalama — ayarlayın."
type: docs
url: /tr/python-net/guides/customize/
is_root: false
weight: 60
---


GroupDocs.Watermark, bir filigranın nasıl göründüğünü ve nerede görüneceğini kontrol etmenizi sağlar. Renk, yazı tipi, hizalama, dönüş, opaklık ve ölçeklendirmeyi belgenizin stiline uygun şekilde ayarlayın.

## Customize text watermarks

[`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) özelliklerini `foreground_color`, `opacity`, `rotate_angle`, `sizing_type`, `scale_factor`, `horizontal_alignment`, `vertical_alignment`, `x`, `y`, `width`, `height` ve `consider_parent_margins` gibi kullanın. Aşağıdaki örnek, bir "DRAFT" filigranını sayfaya ölçeklendirir, 45° döndürür ve yarı saydam yapar.

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
        # Filigranı sayfaya göre ölçeklendirin ve döndürün
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

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) tıklayın.

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

Görüntü filigranları aynı konumlandırma, döndürme ve saydamlık özelliklerini destekler. Bir logo, damga veya mühürü tam olarak ihtiyacınız olan yere yerleştirin:

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

`sample.pdf` ve `stamp.png` bu örnekte kullanılan örnek dosyalardır. [sample.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) ve [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/stamp.png) indirin.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 268 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_image_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}
