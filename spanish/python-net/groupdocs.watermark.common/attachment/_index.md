---
title: "Clase Attachment"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa un archivo adjunto a un documento."
type: docs
url: /es/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

Representa un archivo adjunto a un documento.

Más información

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

El tipo Attachment expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | Carga un contenido del archivo adjunto. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | Carga un contenido del archivo adjunto con las opciones de carga especificadas. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | Carga un contenido del archivo adjunto con las opciones de carga y configuraciones especificadas. |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | Recupera la información sobre un documento almacenado en el archivo adjunto. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | El contenido del archivo adjunto. |

### Ejemplo

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

### Ver también
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
