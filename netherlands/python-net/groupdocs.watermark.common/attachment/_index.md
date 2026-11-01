---
title: "Attachment-klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt een bestand voor dat aan een document is gekoppeld."
type: docs
url: /nl/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

Stelt een bestand voor dat aan een document is gekoppeld.

Meer info

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

Het Attachment-type toont de volgende leden:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | Laadt een inhoud van het bijgevoegde bestand. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | Laadt een inhoud van het bijgevoegde bestand met de opgegeven laadopties. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | Laadt een inhoud van het bijgevoegde bestand met de opgegeven laadopties en instellingen. |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | Haalt de informatie op over een document dat is opgeslagen in het bijgevoegde bestand. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | De inhoud van het bijgevoegde bestand. |

### Voorbeeld

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

### Zie ook
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
