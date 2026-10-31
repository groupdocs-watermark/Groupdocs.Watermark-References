---
title: "from_extension मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "फ़ाइल एक्सटेंशन को फ़ाइल प्रकार से मैप करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

फ़ाइल एक्सटेंशन को फ़ाइल प्रकार से मैप करता है।

```python
def from_extension(cls, extension):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| extension | `str` | फ़ाइल एक्सटेंशन (डॉट "." सहित)। |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| उठाता है | विवरण |
| :- | :- |
| `ValueError` | जब `extension` null या खाली स्ट्रिंग हो तो फेंका जाता है। |

### संबंधित देखें
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
