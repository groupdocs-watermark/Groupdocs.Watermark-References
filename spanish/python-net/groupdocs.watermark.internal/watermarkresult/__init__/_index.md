---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase WatermarkResult."
type: docs
url: /es/python-net/groupdocs.watermark.internal/watermarkresult/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/).

```python
def __init__(self):
    ...
```

## __init__ {#source_document_size-processing_time-final_document_size-number_watermarks_applied}

Inicializa una nueva instancia de WatermarkResult con valores específicos.

```python
def __init__(self, source_document_size, processing_time, final_document_size, number_watermarks_applied):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_document_size | `int` | El tamaño del documento fuente en bytes. |
| processing_time | `timedelta` | El tiempo de procesamiento en milisegundos. |
| final_document_size | `int` | El tamaño del documento procesado final en bytes. |
| number_watermarks_applied | `int` | El número total de marcas de agua aplicadas al documento. |

### Ver también
* class [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/)
