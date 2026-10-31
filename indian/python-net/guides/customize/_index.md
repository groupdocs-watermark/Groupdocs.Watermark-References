---
title: "वॉटरमार्क को अनुकूलित करें"
linkTitle: "Customize watermarks"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "GroupDocs.Watermark for Python के माध्यम से .NET का उपयोग करके टेक्स्ट या छवि वॉटरमार्क की उपस्थिति और स्थिति — रंग, फ़ॉन्ट, घूर्णन, अपारदर्शिता, आकार, और संरेखण — को समायोजित करें।"
type: docs
url: /hi/python-net/guides/customize/
is_root: false
weight: 60
---


GroupDocs.Watermark आपको यह नियंत्रित करने देता है कि वॉटरमार्क कैसे दिखता है और कहाँ प्रकट होता है। अपने दस्तावेज़ की शैली से मेल खाने के लिए रंग, फ़ॉन्ट, संरेखण, घूर्णन, अपारदर्शिता, और स्केलिंग को समायोजित करें।

## Customize text watermarks

[`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) प्रॉपर्टीज़ जैसे `foreground_color`, `opacity`, `rotate_angle`, `sizing_type`, `scale_factor`, `horizontal_alignment`, `vertical_alignment`, `x`, `y`, `width`, `height`, और `consider_parent_margins` का उपयोग करें। नीचे दिया गया उदाहरण "DRAFT" वॉटरमार्क को पृष्ठ के अनुसार स्केल करता है, उसे 45° घुमाता है, और आधा पारदर्शी बनाता है।

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
        # वॉटरमार्क को पृष्ठ के सापेक्ष स्केल करें और उसे घुमाएँ
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

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) क्लिक करें।

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

इमेज वॉटरमार्क समान पोजिशनिंग, रोटेशन और अपारदर्शिता गुणों का समर्थन करते हैं। एक लोगो, स्टैम्प, या सील को बिल्कुल उसी जगह रखें जहाँ आपको चाहिए:

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
{{< tab \"sample.pdf\" >}}

`sample.pdf` और `stamp.png` इस उदाहरण में उपयोग की गई नमूना फ़ाइलें हैं। डाउनलोड करें [sample.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) और [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/stamp.png)।

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 268 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_image_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}
