---
title: "नमस्ते, दुनिया!"
linkTitle: "Hello, World!"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "GroupDocs.Watermark for Python via .NET के साथ जल्दी शुरू करें, एक सरल उदाहरण बनाकर और चलाकर।"
type: docs
url: /hi/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
एक "Hello, World!" उदाहरण अक्सर GroupDocs.Watermark for Python via .NET का अन्वेषण करते समय पहला कदम होता है। यह आपके विकास वातावरण की सही सेटअप की पुष्टि करने और यह सुनिश्चित करने के लिए एक सरल परीक्षण के रूप में कार्य करता है कि लाइब्रेरी अपेक्षित रूप से कार्य कर रही है।

## Overview
GroupDocs.Watermark for Python via .NET आपको विभिन्न दस्तावेज़ फ़ॉर्मेट में वॉटरमार्क जोड़ने, खोजने और हटाने की अनुमति देता है। विभिन्न उपयोग मामलों के लिए यह बहुमुखी बनाता है एक विस्तृत श्रृंखला के [समर्थित फ़ॉर्मेट](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/)।

## How to add a watermark
निम्नलिखित चरण दर्शाते हैं कि GroupDocs.Watermark for Python via .NET का उपयोग करके दस्तावेज़ में टेक्स्ट वॉटरमार्क कैसे जोड़ें:

1. आवश्यक `groupdocs.watermark` क्लासेस को इम्पोर्ट करें।
2. नमूना दस्तावेज़ के पथ के साथ एक [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) खोलें।
3. इच्छित टेक्स्ट और फ़ॉन्ट के साथ एक [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) बनाएं, और उसे स्टाइल करें।
4. वॉटरमार्क को `add()` के साथ लागू करें।
5. परिणाम को सहेजें।

## Complete example
नीचे दिया गया उदाहरण अर्ध-पारदर्शी, तिरछा \"Hello, Watermark!\" टेक्स्ट वॉटरमार्क जोड़ता है और परिणाम सहेजता है:

{{< tabs "code-example-hello-world" >}}
{{< tab "hello_world.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # दस्तावेज़ खोलें, एकल टेक्स्ट वॉटरमार्क जोड़ें, और परिणाम सहेजें
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("Hello, Watermark!", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermark.rotate_angle = 45.0
        watermarker.add(watermark)
        watermarker.save("./output.pdf")

    print("Watermark added successfully. Output saved to ./output.pdf.")

if __name__ == "__main__":
    hello_world()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

वॉटरमार्क `output.pdf` के समान PDF फ़ॉर्मेट में वापस सहेजा जाता है। किसी अलग दस्तावेज़ को स्टैम्प करने के लिए, इनपुट पथ और आउटपुट एक्सटेंशन बदलें — GroupDocs.Watermark इनपुट दस्तावेज़ के फ़ॉर्मेट में सहेजता है।

## Additional resources
यह डेमो GroupDocs.Watermark for Python via .NET के [कोड नमूनों](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/) को संदर्भित करता है।
