---
title: "add_link método"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Añade un archivo adjunto mediante un enlace (el documento no contendrá el contenido del archivo adjunto)."
type: docs
url: /es/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

Añade un archivo adjunto mediante un enlace (el documento no contendrá el contenido del archivo adjunto).

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_full_name | `str` | La ruta del archivo vinculado. |
| preview_image_content | `list[int]` | La imagen de vista previa del archivo adjunto como una matriz de bytes. |
| x | `float` | La coordenada x del marco del adjunto (en puntos). |
| y | `float` | La coordenada y del marco del adjunto (en puntos). |
| width | `float` | El ancho del marco del adjunto en puntos. |
| height | `float` | La altura del marco del adjunto en puntos. |

### Ejemplo

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

### Ver también
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
