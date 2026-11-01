---
title: "método get_document_info"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Obtiene la información sobre el formato del documento cargado."
type: docs
url: /es/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Obtiene la información sobre el formato del documento cargado.

Obtenga más información sobre la obtención de la información del documento.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### Ejemplo

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### Ver también
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
