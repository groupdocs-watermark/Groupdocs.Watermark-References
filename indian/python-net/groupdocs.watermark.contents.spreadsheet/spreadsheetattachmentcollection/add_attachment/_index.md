---
title: "add_attachment मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "SpreadsheetWorksheet में एक अटैचमेंट जोड़ता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

SpreadsheetWorksheet में एक अटैचमेंट जोड़ता है।

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_content | `list[int]` | संलग्न की जाने वाली फ़ाइल की सामग्री को शामिल करने वाले बाइट्स। |
| source_full_name | `str` | str संलग्न फ़ाइल का पूर्ण नाम (एक्सटेंशन का उपयोग फ़ाइल खोलने के लिए उपयुक्त एप्लिकेशन निर्धारित करने में किया जाता है)। |
| preview_image_content | `list[int]` | संलग्न फ़ाइल की प्रीव्यू इमेज को बाइट एरे के रूप में बाइट्स। |
| x | `float` | int संलग्न फ़्रेम का x‑कोऑर्डिनेट (पॉइंट्स में)। |
| y | `float` | int संलग्न फ़्रेम का y‑कोऑर्डिनेट (पॉइंट्स में)। |
| width | `float` | int संलग्न फ़्रेम की चौड़ाई (पॉइंट्स में)। |
| height | `float` | int संलग्न फ़्रेम की ऊँचाई (पॉइंट्स में)। |

**Returns:** None.

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

def add_attachment():
    with Watermarker("./sample.xlsx", SpreadsheetLoadOptions()) as watermarker:
        content = watermarker.get_content()
        with open("./sample.docx", "rb") as f:
            data = f.read()
        with open("./preview.png", "rb") as f:
            preview = f.read()
        # फ़ाइल को पहले वर्कशीट में एम्बेड करें, जिसे उसकी प्रीव्यू इमेज के रूप में दिखाया जाएगा
        # x=50, y=20 पर, 100 x 120 फ्रेम के साथ
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### संबंधित देखें
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
