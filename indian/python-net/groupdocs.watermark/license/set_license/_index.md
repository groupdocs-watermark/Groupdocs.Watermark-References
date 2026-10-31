---
title: "set_license मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "वर्तमान प्रक्रिया में एक लाइसेंस लागू करें।"
type: docs
url: /hi/python-net/groupdocs.watermark/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

वर्तमान प्रक्रिया में एक लाइसेंस लागू करें।

```python
def set_license(self, license_source):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| license_source |  | या तो एक स्ट्रिंग पाथ जो ``.lic`` फ़ाइल की ओर इशारा करता है या एक रीडेबल फ़ाइल-समतुल्य ऑब्जेक्ट जो लाइसेंस बाइट्स प्रदान करता है। फ़ाइल-समतुल्य इनपुट को ब्रिज को पास करने से पहले एक अस्थायी फ़ाइल में लिखा जाता है। |

| उठाता है | विवरण |
| :- | :- |
| `TypeError` | यदि ``license_source`` न तो एक स्ट्रिंग पाथ है और न ही एक रीडेबल फ़ाइल-समतुल्य ऑब्जेक्ट। |

### संबंधित देखें
* class [`License`](/watermark/python-net/groupdocs.watermark/license/)
