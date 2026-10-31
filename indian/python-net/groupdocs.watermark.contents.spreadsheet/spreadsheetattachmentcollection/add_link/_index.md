---
title: "add_link मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "एक लिंक द्वारा अटैचमेंट जोड़ता है (दस्तावेज़ में अटैच्ड फ़ाइल की सामग्री नहीं होगी)।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

एक लिंक द्वारा अटैचमेंट जोड़ता है (दस्तावेज़ में अटैच्ड फ़ाइल की सामग्री नहीं होगी)।

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| source_full_name | `str` | लिंक्ड फ़ाइल पथ। |
| preview_image_content | `list[int]` | संलग्न फ़ाइल का पूर्वावलोकन चित्र बाइट एरे के रूप में। |
| x | `float` | संलग्न फ़्रेम का x‑कोऑर्डिनेट (पॉइंट्स में)। |
| y | `float` | संलग्न फ़्रेम का y‑कोऑर्डिनेट (पॉइंट्स में)। |
| width | `float` | अटैचमेंट फ्रेम की चौड़ाई पॉइंट्स में। |
| height | `float` | अटैचमेंट फ्रेम की ऊँचाई पॉइंट्स में। |

### उदाहरण

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions
import groupdocs.watermark.contents.spreadsheet as gwc_xls

load_options = SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    content = watermarker.get_content()
    worksheet = content.worksheets[0]
    with open("document_preview.png", "rb") as f_prev:
        worksheet.attachments.add_link(
            "document.docx",
            f_prev.read(),
            50,
            100,
            200,
            400,
        )
    watermarker.save("output.xlsx")
```

### संबंधित देखें
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
