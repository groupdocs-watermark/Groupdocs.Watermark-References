---
title: "Attachment-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar en fil som är bifogad till ett dokument."
type: docs
url: /sv/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

Representerar en fil som är bifogad till ett dokument.

Läs mer

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

Attachment-typen visar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | Läser in ett innehåll från den bifogade filen. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | Läser in ett innehåll från den bifogade filen med de angivna inläsningsalternativen. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | Läser in ett innehåll från den bifogade filen med de angivna inläsningsalternativen och inställningarna. |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | Hämtar information om ett dokument som lagras i den bifogade filen. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | Innehållet i den bifogade filen. |

### Exempel

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

### Se även
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
