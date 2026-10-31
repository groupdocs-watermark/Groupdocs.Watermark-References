---
title: "تخصيص العلامات المائية"
linkTitle: "Customize watermarks"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "ضبط مظهر وموقع العلامة المائية النصية أو الصورة — اللون، الخط، الدوران، الشفافية، الحجم، والمحاذاة — باستخدام GroupDocs.Watermark للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/customize/
is_root: false
weight: 60
---


يتيح لك GroupDocs.Watermark التحكم في شكل العلامة المائية ومكان ظهورها. اضبط اللون، الخط، المحاذاة، الدوران، الشفافية، والتحجيم لتتناسب مع نمط مستندك.

## Customize text watermarks

استخدم خصائص [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) مثل `foreground_color`، `opacity`، `rotate_angle`، `sizing_type`، `scale_factor`، `horizontal_alignment`، `vertical_alignment`، `x`، `y`، `width`، `height`، و `consider_parent_margins`. المثال أدناه يوسع علامة مائية \"DRAFT\" لتغطي الصفحة، يدورها 45°, ويجعلها نصف شفافة.

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
        # قُم بتكبير العلامة المائية نسبة إلى الصفحة وقم بتدويرها
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

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر على [هنا](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) لتحميله.

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

تدعم العلامات المائية للصور نفس خصائص التموضع والدوران والشفافية. ضع الشعار أو الختم أو الختم الرسمي بالضبط حيث تحتاجه:

{{< tabs \"code-example-customize-image\">}}
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

`sample.pdf` و `stamp.png` هما ملفات العينة المستخدمة في هذا المثال. قم بتنزيل [sample.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) و [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/stamp.png).

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 268 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_image_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}
