---
title: "समर्थित फ़ाइल फ़ॉर्मेट प्राप्त करें"
linkTitle: "Get supported file formats"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "GroupDocs.Watermark for Python via .NET द्वारा समर्थित सभी फ़ाइल फ़ॉर्मेट की सूची बनाएं।"
type: docs
url: /hi/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


GroupDocs.Watermark द्वारा समर्थित फ़ाइल फ़ॉर्मेट की पूरी सूची शीघ्रता से प्राप्त करें। यह आपके एप्लिकेशन को दस्तावेज़ प्रोसेस करने से पहले गतिशील रूप से संगतता जांचने की अनुमति देता है — उदाहरण के लिए, उपयोगकर्ता द्वारा अपलोड की गई फ़ाइलों को मान्य करने के लिए।

## List supported file formats

`FileType.get_supported_file_types()` सभी समर्थित फ़ाइल प्रकार लौटाता है। प्रत्येक आइटम अपना `extension` और एक उपयोगी विवरण प्रदर्शित करता है।

{{< tabs \"code-example-get-supported-file-formats\">}}
{{< tab \"list_supported_formats.py\" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # लाइब्रेरी द्वारा खोले जा सकने वाले प्रत्येक फ़ाइल प्रकार को सूचीबद्ध करें
    supported_file_types = FileType.get_supported_file_types()
    for file_type in sorted(supported_file_types, key=lambda x: x.extension):
        print(file_type)

if __name__ == "__main__":
    list_supported_formats()
```
{{< /tab >}}
{{< tab \"list-supported-formats.txt\" >}}
```text
Bmp (.bmp) - Image
Doc (.doc) - WordProcessing
Docm (.docm) - WordProcessing
Docx (.docx) - WordProcessing
Dot (.dot) - WordProcessing
Dotm (.dotm) - WordProcessing
Dotx (.dotx) - WordProcessing
Eml (.eml) - Email
Emlx (.emlx) - Email
Gif (.gif) - Image
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/get-supported-file-formats/list_supported_formats/list-supported-formats.txt)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Build flexible applications that validate user-uploaded files and tell the user whether watermarking is supported.
