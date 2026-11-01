---
title: "add_attachment método"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Añade un archivo adjunto al SpreadsheetWorksheet."
type: docs
url: /es/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

Añade un archivo adjunto al SpreadsheetWorksheet.

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_content | `list[int]` | bytes que contienen el contenido del archivo a adjuntar. |
| source_full_name | `str` | str nombre completo del archivo adjunto (la extensión se usa para determinar la aplicación adecuada para abrir el archivo). |
| preview_image_content | `list[int]` | bytes imagen de vista previa del archivo adjunto como una matriz de bytes. |
| x | `float` | int coordenada x del marco del adjunto (en puntos). |
| y | `float` | int coordenada y del marco del adjunto (en puntos). |
| width | `float` | int ancho del marco del adjunto (en puntos). |
| height | `float` | int altura del marco del adjunto (en puntos). |

**Returns:** None.

### Ejemplo

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
        # Incruste el archivo en la primera hoja de cálculo, mostrada como su imagen de vista previa
        # en x=50, y=20 con un marco de 100 x 120
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### Ver también
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
