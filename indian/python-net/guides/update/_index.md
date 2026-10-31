---
title: "वॉटरमार्क अपडेट करें"
linkTitle: "Update watermarks"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "GroupDocs.Watermark for Python via .NET का उपयोग करके मौजूदा टेक्स्ट या इमेज वॉटरमार्क खोजें और उन्हें अपडेट करें।"
type: docs
url: /hi/python-net/guides/update/
is_root: false
weight: 90
---


आप दस्तावेज़ में मौजूदा वॉटरमार्क खोज सकते हैं और उन्हें उसी जगह संशोधित कर सकते हैं — उदाहरण के लिए, टेक्स्ट वॉटरमार्क के टेक्स्ट को बदलें या इमेज वॉटरमार्क की इमेज बदलें।

## Update text watermarks

वॉटरमार्क को उसके टेक्स्ट कंटेंट से खोजें, फिर प्रत्येक मिलान को नया मान असाइन करें। नीचे दिया गया उदाहरण एक दस्तावेज़ खोलता है जिसमें पहले से "CONFIDENTIAL" वॉटरमार्क है और उसे "APPROVED" से बदल देता है।

{{< tabs "code-example-update">}}
{{< tab "update_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def update_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        # उन वॉटरमार्क को खोजें जिनका टेक्स्ट मानदंड से मेल खाता है
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s).")
        for watermark in possible:
            try:
                watermark.text = "APPROVED"
            except Exception:
                # कुछ पाए गए एंटिटीज़ टेक्स्ट एडिटिंग का समर्थन नहीं करतीं — उन्हें छोड़ दें
                pass
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    update_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` इस उदाहरण में उपयोग की गई सैंपल फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.pdf) क्लिक करें।

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 444 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

## Update image watermarks

इमेज वॉटरमार्क को परसेप्चुअल हैशिंग ([`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)) से पाया जा सकता है और `image_data` को नए बाइट्स असाइन करके अपडेट किया जा सकता है। नीचे दिया गया उदाहरण लोगो वॉटरमार्क को खोजता है और उसे "APPROVED" स्टैम्प से बदल देता है:

{{< tabs \"code-example-update-image\">}}
{{< tab \"update_image_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def update_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        with open("./stamp.png", "rb") as f:
            image_data = f.read()
        for watermark in possible:
            try:
                watermark.image_data = image_data
            except Exception:
                # कुछ पाए गए इकाइयाँ छवि संपादन का समर्थन नहीं करतीं — उन्हें छोड़ दें
                pass
        watermarker.save("./output.docx")

if __name__ == "__main__":
    update_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx`, `logo.png`, और `stamp.png` इस उदाहरण में उपयोग की गई नमूना फ़ाइलें हैं। डाउनलोड करें [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.docx), [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/logo.png), और [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/stamp.png)।

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 19 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
