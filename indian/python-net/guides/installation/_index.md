---
title: "इंस्टॉल GroupDocs.Watermark for Python via .NET"
linkTitle: "Installation"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "इंस्टॉल GroupDocs.Watermark for Python via .NET Windows, Linux, या macOS पर — PyPI से या प्री-डाउनलोडेड व्हील से, जिसमें Intel और Apple Silicon बिल्ड्स शामिल हैं।"
type: docs
url: /hi/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Watermark for Python via .NET को [PyPI](https://pypi.org/project/groupdocs-watermark-net/) पर एक प्री-बिल्ट व्हील के रूप में वितरित किया जाता है। PyPI इंडेक्स प्रत्येक समर्थित प्लेटफ़ॉर्म के लिए एक अलग व्हील होस्ट करता है, और `pip` स्वचालित रूप से सही वाला चुनता है। प्रत्येक व्हील स्व-निहित है: यह एम्बेडेड रनटाइम और सभी प्रबंधित डिपेंडेंसीज़ को बंडल करता है, इसलिए कोई Microsoft Office, OpenOffice, या अलग रनटाइम इंस्टॉल करने की आवश्यकता नहीं है।

इंस्टॉल करने से पहले, [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) की समीक्षा करें। व्हील्स को Linux के साथ glibc 2.27 या उससे नया, या macOS 12 या उससे नया, और इंस्टॉल करने के लिए pip 20.3 या उससे नया चाहिए। Linux पर, ICU, fontconfig, `libgdiplus` और Microsoft कोर फ़ॉन्ट्स इंस्टॉल करें; macOS पर, `mono-libgdiplus` इंस्टॉल करें (देखें [Platform Prerequisites](#platform-prerequisites)).

## Install Package from PyPI

एक टर्मिनल खोलें और अपने प्लेटफ़ॉर्म के लिए इंस्टॉल कमांड चलाएँ:

{{< tabs \"install-pypi\">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-watermark-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-watermark-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-watermark-net
```
{{< /tab >}}
{{< /tabs >}}

कमांड चलाने के बाद आपको इस तरह का आउटपुट दिखना चाहिए:

```bash
Collecting groupdocs-watermark-net
  Downloading groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl (138.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.9/138.9 MB 3.1 MB/s eta 0:00:00
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

व्हील फ़ाइल नाम में एक प्लेटफ़ॉर्म सफ़िक्स शामिल होगा जो आपके ऑपरेटिंग सिस्टम से मेल खाता है — उदाहरण के लिए Linux पर `manylinux_2_27_x86_64`, Apple Silicon पर `macosx_12_0_arm64`, या 64-बिट Windows पर `win_amd64`।

## Add the Package to `requirements.txt`

पुनरुत्पादनीय वातावरण के लिए, अपने `requirements.txt` में पैकेज संस्करण पिन करें:

```txt
groupdocs-watermark-net==26.10.0
```

फिर सभी डिपेंडेंसीज़ को एक कदम में इंस्टॉल करें:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

यदि आपका बिल्ड वातावरण PyPI तक नहीं पहुँच सकता, तो उपयुक्त व्हील को [GroupDocs Releases website](https://releases.groupdocs.com/watermark/python-net/) से डाउनलोड करें और स्थानीय रूप से इंस्टॉल करें। व्हील्स निम्नलिखित चार प्लेटफ़ॉर्म के लिए प्रकाशित किए गए हैं:

| प्लेटफ़ॉर्म | व्हील फ़ाइल नाम समाप्त होता है | सबसे पुराना सिस्टम |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

26.10 से फ़ाइल नाम यह दर्शाते हैं कि प्रत्येक व्हील किस सबसे पुराने सिस्टम पर चलता है, इसलिए pip 20.3 या उससे नया पहले ही एक पुराने व्हील को अस्वीकार कर देता है बजाय ऐसे रनटाइम को इंस्टॉल करने के जो शुरू नहीं हो सकता। 26.6 तक के व्हील्स को `manylinux1_x86_64`, `macosx_10_14_x86_64` और `macosx_11_0_arm64` टैग किया गया था।

डाउनलोड किया गया व्हील अपने प्रोजेक्ट फ़ोल्डर में रखें, फिर इसे इंस्टॉल करें:

{{< tabs \"install-wheel\">}}
{{< tab \"Windows (64-bit)\" >}}
```ps
py -m pip install .\groupdocs_watermark_net-26.10.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab \"Linux (glibc)\" >}}
```bash
python3 -m pip install ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
```
{{< /tab >}}
{{< tab \"macOS (Intel)\" >}}
```bash
python3 -m pip install ./groupdocs_watermark_net-26.10.0-py3-none-macosx_12_0_x86_64.whl
```
{{< /tab >}}
{{< tab \"macOS (Apple Silicon)\" >}}
```bash
python3 -m pip install ./groupdocs_watermark_net-26.10.0-py3-none-macosx_12_0_arm64.whl
```
{{< /tab >}}
{{< /tabs >}}

व्हील फ़ाइल का स्पष्ट रूप से नाम दें: PowerShell मूल कमांड के लिए `*` वाइल्डकार्ड का विस्तार नहीं करता, इसलिए `pip install groupdocs_watermark_net-*.whl` वहाँ विफल हो जाता है।

अपेक्षित आउटपुट (Linux):

```bash
Processing ./groupdocs_watermark_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-watermark-net
Successfully installed groupdocs-watermark-net-26.10.0
```

## Platform Prerequisites

Windows पर कोई अतिरिक्त कदम आवश्यक नहीं हैं। Linux पर, ICU, fontconfig, `libgdiplus` और Microsoft कोर फ़ॉन्ट्स इंस्टॉल करें; macOS पर, `mono-libgdiplus`। [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) पृष्ठ बताता है कि प्रत्येक के लिए कौन सी सुविधाएँ आवश्यक हैं।

{{< tabs \"platform-prereqs\">}}
{{< tab \"Linux\" >}}
```bash
# Debian: ttf-mscorefonts-installer contrib घटक में है
sudo sed -i '/^Components:/s/main/main contrib/' /etc/apt/sources.list.d/debian.sources
sudo apt-get update
sudo apt-get install -y libicu-dev libfontconfig1 libgdiplus ttf-mscorefonts-installer
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
brew install mono-libgdiplus
```
{{< /tab >}}
{{< /tabs >}}

## Verify the Installation

पैकेज सही तरीके से आयात हुआ है यह पुष्टि करें और स्थापित संस्करण जांचें:

```bash
python -c "import groupdocs.watermark; print('GroupDocs.Watermark is ready')"
```

आप `pip show groupdocs-watermark-net` के साथ स्थापित पैकेज की सूची भी देख सकते हैं ताकि संस्करण और स्थान की पुष्टि हो सके।

## Next Steps

- Follow the [Hello, World!](/watermark/python-net/guides/hello-world/) guide to add your first watermark.
- Read the [Features Overview](/watermark/python-net/guides/features-overview/) to see everything you can do.
- Clone the [examples repository](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/watermark/python-net/how-to-run-examples/) to try every documented scenario locally.
