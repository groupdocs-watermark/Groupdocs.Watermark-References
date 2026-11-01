---
title: "propiedad create_page_stream"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "El delegado de creación del flujo de página usado para obtener un flujo de escritura para cada página renderizada."
type: docs
url: /es/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

El delegado de creación del flujo de página usado para obtener un flujo de escritura para cada página renderizada.

GroupDocs.Watermark renderiza las páginas del documento como imágenes. Proporcione un callable que reciba un número de página (`int`) y devuelva un flujo `io.RawIOBase` escribible; la biblioteca escribe la imagen renderizada en el flujo y lo cierra.

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### Ver también
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
