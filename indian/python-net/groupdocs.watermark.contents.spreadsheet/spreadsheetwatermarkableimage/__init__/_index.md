---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट छवि डेटा का उपयोग करके SpreadsheetWatermarkableImage क्लास का नया उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

निर्दिष्ट इमेज डेटा का उपयोग करके [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, image_data):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| image_data | `list[int]` | `SpreadsheetWatermarkableImage` बनाने के लिए अनसाइन्ड बाइट्स की एरे। |

### उदाहरण

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### संबंधित देखें
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
