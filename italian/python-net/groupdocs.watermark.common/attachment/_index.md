---
title: "Classe Attachment"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta un file allegato a un documento."
type: docs
url: /it/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

Rappresenta un file allegato a un documento.

Maggiori informazioni

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

Il tipo Attachment espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | Carica un contenuto dal file allegato. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | Carica un contenuto dal file allegato con le opzioni di caricamento specificate. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | Carica un contenuto dal file allegato con le opzioni di caricamento e le impostazioni specificate. |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | Recupera le informazioni su un documento memorizzato nel file allegato. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | Il contenuto del file allegato. |

### Esempio

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

### Vedi anche
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
