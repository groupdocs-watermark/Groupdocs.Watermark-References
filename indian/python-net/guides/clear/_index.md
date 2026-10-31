---
title: "वॉटरमार्क हटाएँ"
linkTitle: "Clear watermarks"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "GroupDocs.Watermark for Python via .NET का उपयोग करके मौजूदा टेक्स्ट या इमेज वॉटरमार्क खोजें और हटाएँ।"
type: docs
url: /hi/python-net/guides/clear/
is_root: false
weight: 100
---


आप किसी दस्तावेज़ में मौजूदा वॉटरमार्क खोज सकते हैं और उन्हें हटा सकते हैं। नीचे दिया गया उदाहरण "CONFIDENTIAL" टेक्स्ट वॉटरमार्क को खोजता है और उसे हटाता है, जिससे एक साफ़ दस्तावेज़ बनता है।

## Remove text watermarks

खोज परिणामों को उल्टे क्रम में इटरेट करें ताकि किसी आइटम को हटाने से शेष इंडेक्स बदल नें, और प्रत्येक मिलान के लिए `remove()` कॉल करें।

{{< tabs "code-example-clear">}}
{{< tab "clear_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def clear_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        # वस्तुओं को हटाते समय इंडेक्स वैध रहे, इसके लिए उल्टे क्रम में हटाएँ
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    clear_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` इस उदाहरण में उपयोग की गई सैंपल फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.pdf) क्लिक करें।

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 360 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Remove outdated labels such as "Draft" or "Internal Use Only" before sharing a document externally.

## Remove image watermarks

इमेज वॉटरमार्क को परसेप्चुअल हैशिंग से पाया जा सकता है और उसी तरीके से हटाया जा सकता है:

{{< tabs "code-example-clear-image">}}
{{< tab "clear_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        # वस्तुओं को हटाते समय इंडेक्स वैध रहे, इसके लिए उल्टे क्रम में हटाएँ
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")

if __name__ == "__main__":
    clear_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx` और `logo.png` इस उदाहरण में उपयोग की गई सैंपल फ़ाइलें हैं। डाउनलोड करें [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.docx) और [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/logo.png)।

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
