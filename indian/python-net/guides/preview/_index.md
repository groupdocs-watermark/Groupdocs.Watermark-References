---
title: "दस्तावेज़ पूर्वावलोकन"
linkTitle: "Document preview"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "GroupDocs.Watermark for Python via .NET का उपयोग करके दस्तावेज़ पृष्ठों के लिए पूर्वावलोकन छवियां (PNG/JPG/BMP) उत्पन्न करें।"
type: docs
url: /hi/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark दस्तावेज़ पृष्ठों को छवियों के रूप में रेंडर कर सकता है ताकि आप पृष्ठ थंबनेल दिखा सकें बिना दस्तावेज़ को व्यूअर में पूरी तरह खोलें। आप रेंडर को एक `create_page_stream` कॉलबैक के साथ चलाते हैं जो प्रत्येक पृष्ठ के लिए एक लिखने योग्य फ़ाइल स्ट्रीम प्रदान करता है — लाइब्रेरी पृष्ठ छवि को उसमें लिखती है और आपके लिए बंद कर देती है।

## Generate a document preview

एक `create_page_stream` कॉलबैक के साथ [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) सेट करें, `preview_format` चुनें, और रेंडर करने के लिए `page_numbers` की सूची दें।

{{< tabs "code-example-preview">}}
{{< tab "generate_preview.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # प्रत्येक पृष्ठ को रेंडर करने के लिए एक लिखने योग्य फ़ाइल स्ट्रीम प्रदान करें
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई दो‑पृष्ठीय नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab "generate-preview-outputs.zip" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

पृष्ठ छवियों को वर्तमान डायरेक्टरी में लिखा जाता है — अनुरोधित प्रत्येक पृष्ठ के लिए एक PNG। अन्य फ़ॉर्मेट के लिए `PreviewFormats.JPEG` या `PreviewFormats.BMP` उपयोग करें, और रेंडर किए गए आकार को नियंत्रित करने के लिए `options.width` / `options.height` सेट करें।

लाइब्रेरी प्रत्येक फ़ाइल को बंद कर देती है जो `create_page_stream` लौटाता है, एक बार पृष्ठ लिख दिया जाता है। जैसे ही पृष्ठ तैयार हो, उस पर कार्रवाई करने के लिए दूसरा कॉलबैक पास करें: `PreviewOptions(create_page_stream, release_page_stream)` `release_page_stream(page_number, stream)` को कॉल करता है, जिसमें वह ऑब्जेक्ट `create_page_stream` शामिल होता है जो उस पृष्ठ के लिए लौटाया गया था, पूरी छवि उसमें होने के बाद। एक‑आर्ग्युमेंट वाला `release_page_stream(page_number)` भी काम करता है। `create_page_stream` एक `io.BytesIO` भी लौटा सकता है: यह खुला रहता है, और जब `release_page_stream` उसे प्राप्त करता है तब तक पृष्ठ छवि को रखता है।

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
