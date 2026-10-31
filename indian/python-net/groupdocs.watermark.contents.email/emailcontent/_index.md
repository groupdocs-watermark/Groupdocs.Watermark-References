---
title: "EmailContent क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "ईमेल संदेश का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.email/emailcontent/
is_root: false
weight: 70
---


## EmailContent class

ईमेल संदेश का प्रतिनिधित्व करता है।

और अधिक जानें:
- [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
- [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
- [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

EmailContent प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | वर्तमान इंस्टेंस को डिस्पोज़ करता है। ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/) से विरासत में मिला) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | निर्दिष्ट खोज मानदंडों के अनुसार छवियों को खोजता है। खोज उन वस्तुओं में की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में निर्दिष्ट हैं। ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | निर्दिष्ट खोज मानदंडों के अनुसार संभावित वॉटरमार्क को खोजता है। खोज उन वस्तुओं पर की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में सूचीबद्ध हैं। ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) से विरासत में मिला) |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/attachments/) | ईमेल संदेश के सभी अटैचमेंट्स का संग्रह। |
| [bcc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/bcc/) | ईमेल संदेश के BCC (ब्लाइंड कार्बन कॉपी) प्राप्तकर्ताओं का संग्रह। |
| [body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body/) | संदेश बॉडी का सादा पाठ प्रतिनिधित्व। |
| [body_type](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/body_type/) | ईमेल संदेश बॉडी का प्रकार। |
| [cc](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/cc/) | ईमेल संदेश के CC (कार्बन कॉपी) प्राप्तकर्ताओं का संग्रह। |
| [embedded_objects](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/embedded_objects/) | ईमेल संदेश के सभी एम्बेडेड ऑब्जेक्ट्स का संग्रह। |
| [from_](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/from_/) | ईमेल संदेश का प्रेषक पता। |
| [html_body](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/html_body/) | संदेश बॉडी का HTML प्रतिनिधित्व। |
| [subject](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/subject/) | ईमेल संदेश का विषय। |
| [to](/watermark/python-net/groupdocs.watermark.contents.email/emailcontent/to/) | ईमेल संदेश के प्राप्तकर्ताओं का संग्रह। |

### उदाहरण

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.email import EmailLoadOptions
import groupdocs.watermark.contents.email as gwc_email

load_options = EmailLoadOptions()
with gw.Watermarker("message.msg", load_options) as watermarker:
    content = watermarker.get_content()
    # एक अटैचमेंट जोड़ें
    with open("sample.msg", "rb") as f:
        content.attachments.add(f.read(), "sample.msg")
    watermarker.save("output.msg")
```

### संबंधित देखें
* module [`groupdocs.watermark.contents.email`](/watermark/python-net/groupdocs.watermark.contents.email/)
