---
title: "método create_watermarker"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Carga un contenido del archivo adjunto."
type: docs
url: /es/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

Carga un contenido del archivo adjunto.

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### Ejemplo

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

Carga un contenido del archivo adjunto con las opciones de carga especificadas.

```python
def create_watermarker(self, load_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| load_options | `LoadOptions` | Opciones adicionales para usar al cargar el contenido de un adjunto. |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

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

## create_watermarker {#load_options-watermarker_settings}

Carga un contenido del archivo adjunto con las opciones de carga y configuraciones especificadas.

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| load_options | `LoadOptions` | Opciones adicionales para usar al cargar el contenido de un adjunto. |
| watermarker_settings | `WatermarkerSettings` | Configuraciones adicionales para usar al trabajar con el documento cargado. |

**Returns:** The instance of appropriate descendant of `Content` class.

### Ejemplo

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

### Ver también
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
