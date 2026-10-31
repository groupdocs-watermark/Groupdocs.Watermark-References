---
title: "पाठ वॉटरमार्क जोड़ें"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "यह लेख दर्शाता है कि कैसे दस्तावेज़ में एक पाठ वॉटरमार्क जोड़ा जाए और परिणाम को GroupDocs.Watermark for Python via .NET के साथ सहेजा जाए।"
type: docs
url: /hi/python-net/guides/add-text/
is_root: false
weight: 40
---


GroupDocs.Watermark की मुख्य विशेषताओं में से एक है दस्तावेज़ों में पाठ वॉटरमार्क जोड़ना। आप स्थानीय पथ से या स्ट्रीम से दस्तावेज़ों या छवियों में वॉटरमार्क जोड़ सकते हैं। समर्थित फ़ॉर्मेट की पूरी सूची के लिए, देखें [समर्थित दस्तावेज़ फ़ॉर्मेट](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/)।

## Add a text watermark

पाठ वॉटरमार्क जोड़ने के लिए, इन चरणों का पालन करें:

1. दस्तावेज़ को खोलें, उसका पथ (या एक स्ट्रीम) को [Watermarker](https://reference.groupdocs.com/watermark/python-net/) क्लास को पास करके, `with` ब्लॉक का उपयोग करें ताकि दस्तावेज़ स्वतः रिलीज़ हो जाए।
2. इच्छित पाठ और [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/) के साथ एक [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) बनाएं।
3. वॉटरमार्क को स्टाइल करें — उदाहरण के लिए, `foreground_color` और संरेखण सेट करें।
4. वॉटरमार्क लागू करने के लिए `add()` कॉल करें और परिणाम लिखने के लिए `save()` कॉल करें।

{{< tabs "code-example-add-text">}}
{{< tab "add_text_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # पाठ वॉटरमार्क बनाएं और उसे स्टाइल करें
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

प्रोग्राम चलाएँ। निर्दिष्ट पथ पर एक नया वॉटरमार्क किया हुआ दस्तावेज़ दिखाई देता है।

## What's next

GroupDocs.Watermark पाठ वॉटरमार्क के लिए कई अतिरिक्त क्षमताएँ प्रदान करता है — पृष्ठभूमि और अग्रभूमि रंग, कस्टम फ़ॉन्ट, अपारदर्शिता, घूर्णन, टाइलिंग, और निरपेक्ष या सापेक्ष स्थिति। उन्नत गाइड में देखें [पाठ वॉटरमार्क जोड़ना](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/)।
