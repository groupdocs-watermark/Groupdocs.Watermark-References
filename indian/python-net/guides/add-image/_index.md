---
title: "छवि वॉटरमार्क जोड़ें"
linkTitle: "Add image watermarks"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "यह लेख दिखाता है कि कैसे एक दस्तावेज़ में छवि वॉटरमार्क जोड़ें और परिणाम को GroupDocs.Watermark for Python के माध्यम से .NET के साथ सहेजें।"
type: docs
url: /hi/python-net/guides/add-image/
is_root: false
weight: 50
---


GroupDocs.Watermark की मुख्य विशेषताओं में से एक दस्तावेज़ों में छवि वॉटरमार्क जोड़ना है। आप स्थानीय पथ या स्ट्रीम से दस्तावेज़ों या छवियों में वॉटरमार्क जोड़ सकते हैं। समर्थित फ़ॉर्मेट की पूरी सूची के लिए, देखें [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add an image watermark

छवि वॉटरमार्क जोड़ने के लिए, निम्न चरणों का पालन करें:

1. दस्तावेज़ को उसके पथ (या स्ट्रीम) को [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) क्लास में पास करके खोलें।
2. वॉटरमार्क छवि फ़ाइल (या स्ट्रीम) से एक [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) बनाएं।
3. वॉटरमार्क की स्थिति निर्धारित करें — उदाहरण के लिए, `horizontal_alignment`, `vertical_alignment`, और `opacity` सेट करें।
4. वॉटरमार्क लागू करने के लिए `add()` कॉल करें और परिणाम लिखने के लिए `save()` कॉल करें।

{{< tabs "code-example-add-image">}}
{{< tab "add_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # एक लोगो फ़ाइल से छवि वॉटरमार्क बनाएं और उसे केंद्र में रखें
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

`sample.docx` और `logo.png` इस उदाहरण में उपयोग की गई नमूना फ़ाइलें हैं। डाउनलोड करें [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) और [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

GroupDocs.Watermark छवि वॉटरमार्क के लिए अधिक क्षमताएँ प्रदान करता है — स्ट्रीम से लोड करना, स्केलिंग, टाइलिंग, और निरपेक्ष या सापेक्ष स्थिति निर्धारण। उन्नत गाइड में देखें [Adding image watermarks](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/).
