---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de WordProcessingPreviewOptions que hace que el flujo de salida se cierre."
type: docs
url: /es/python-net/groupdocs.watermark.options.word_processing/wordprocessingpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Inicializa una nueva instancia de WordProcessingPreviewOptions que hace que el flujo de salida se cierre.

```python
def __init__(self, create_page_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Crea un flujo para una vista previa de página específica. |

## __init__ {#create_page_stream-release_page_stream}

Inicializa una nueva instancia de la clase WordProcessingPreviewOptions que hace que el flujo de salida se devuelva al cliente para su uso posterior.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Crea un flujo para una vista previa de página específica. |
| release_page_stream | `ReleasePageStream` | Notifica que la generación de la vista previa de la página ha finalizado y obtiene el flujo de salida. |

### Ver también
* class [`WordProcessingPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingpreviewoptions/)
