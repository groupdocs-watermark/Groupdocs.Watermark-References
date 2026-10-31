---
title: "create_watermarker मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "संलग्न फ़ाइल से सामग्री लोड करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

संलग्न फ़ाइल से सामग्री लोड करता है।

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### उदाहरण

```python
    import groupdocs.watermark as gw
    import groupdocs.watermark.contents.pdf as gwc_pdf
    import groupdocs.watermark.watermarks as gww

    watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))

    with gw.Watermarker("document.pdf") as watermarker:
        pdf_content = watermarker.get_content()
        for attachment in pdf_content.attachments:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    ```

## create_watermarker {#load_options}

निर्दिष्ट लोड विकल्पों के साथ संलग्न फ़ाइल से सामग्री लोड करता है।

```python
def create_watermarker(self, load_options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| load_options | `LoadOptions` | अटैचमेंट कंटेंट लोड करते समय उपयोग करने के अतिरिक्त विकल्प। |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

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

## create_watermarker {#load_options-watermarker_settings}

निर्दिष्ट लोड विकल्पों और सेटिंग्स के साथ संलग्न फ़ाइल से सामग्री लोड करता है।

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| load_options | `LoadOptions` | अटैचमेंट कंटेंट लोड करते समय उपयोग करने के अतिरिक्त विकल्प। |
| watermarker_settings | `WatermarkerSettings` | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के अतिरिक्त सेटिंग्स। |

**Returns:** The instance of appropriate descendant of `Content` class.

### उदाहरण

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww

watermark = gww.TextWatermark("Sample watermark", gww.Font("Arial", 19.0))

with gw.Watermarker("document.pdf") as watermarker:
    pdf_content = watermarker.get_content()
    for attachment in pdf_content.attachments:
        with attachment.create_watermarker() as attached:
            attached.add(watermark)
            attached.save()
    watermarker.save("output.pdf")
```

### संबंधित देखें
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
