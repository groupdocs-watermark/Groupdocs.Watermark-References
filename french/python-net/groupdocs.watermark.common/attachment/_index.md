---
title: "Classe Attachment"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente un fichier joint à un document."
type: docs
url: /fr/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

Représente un fichier joint à un document.

En savoir plus

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

Le type Attachment expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | Charge un contenu depuis le fichier joint. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | Charge un contenu depuis le fichier joint avec les options de chargement spécifiées. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | Charge un contenu depuis le fichier joint avec les options de chargement et les paramètres spécifiés. |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | Récupère les informations sur un document stocké dans le fichier joint. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | Le contenu du fichier joint. |

### Exemple

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

### Voir aussi
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
