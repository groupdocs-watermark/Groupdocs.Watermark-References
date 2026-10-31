---
title: "Attachment क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "एक दस्तावेज़ से जुड़ी फ़ाइल को दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

एक दस्तावेज़ से जुड़ी फ़ाइल को दर्शाता है।

और अधिक जानें

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

Attachment प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | संलग्न फ़ाइल से सामग्री लोड करता है। |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | निर्दिष्ट लोड विकल्पों के साथ संलग्न फ़ाइल से सामग्री लोड करता है। |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | निर्दिष्ट लोड विकल्पों और सेटिंग्स के साथ संलग्न फ़ाइल से सामग्री लोड करता है। |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | संलग्न फ़ाइल में संग्रहीत दस्तावेज़ की जानकारी प्राप्त करता है। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | संलग्न फ़ाइल की सामग्री। |

### उदाहरण

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.pdf import PdfLoadOptions
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww
from groupdocs.watermark.common import FileType

watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))
load_options = PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    pdf_content = watermarker.get_content()
    for attachment in pdf_content.attachments:
        info = attachment.get_document_info()
        if info.file_type != FileType.UNKNOWN and not info.is_encrypted:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    watermarker.save("output.pdf")
```

### संबंधित देखें
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
