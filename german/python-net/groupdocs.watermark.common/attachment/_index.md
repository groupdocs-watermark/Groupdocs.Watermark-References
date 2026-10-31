---
title: "Attachment-Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt eine an ein Dokument angehängte Datei dar."
type: docs
url: /de/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

Stellt eine an ein Dokument angehängte Datei dar.

Mehr erfahren

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

Der Attachment‑Typ stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | Lädt einen Inhalt aus der angehängten Datei. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | Lädt einen Inhalt aus der angehängten Datei mit den angegebenen Ladeoptionen. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | Lädt einen Inhalt aus der angehängten Datei mit den angegebenen Ladeoptionen und Einstellungen. |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | Ruft die Informationen über ein im angehängten Datei gespeichertes Dokument ab. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | Der Inhalt der angehängten Datei. |

### Beispiel

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

### Siehe auch
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
