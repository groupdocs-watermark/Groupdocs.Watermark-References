---
title: "Clase IDocumentInfo"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Proporciona los métodos necesarios para obtener información básica del documento."
type: docs
url: /es/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

Proporciona los métodos necesarios para obtener información básica del documento.

Más información: Obtener información del documento.

El tipo IDocumentInfo expone los siguientes miembros:

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | La descripción del formato de archivo. |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | La propiedad indica si el documento está cifrado y requiere una contraseña para abrirlo. |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | El recuento total de páginas. |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | La colección de descripciones de páginas del documento. |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | El tamaño del documento en bytes. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### Ver también
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
