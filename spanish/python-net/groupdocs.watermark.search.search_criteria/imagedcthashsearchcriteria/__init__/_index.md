---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de ImageDctHashSearchCriteria con una ruta de archivo especificada."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Inicializa una nueva instancia de ImageDctHashSearchCriteria con una ruta de archivo especificada.

```python
def __init__(self, file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo desde la cual cargar la imagen. |

### Ejemplo

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

Inicializa una nueva instancia de ImageDctHashSearchCriteria con el flujo de imagen proporcionado.

```python
def __init__(self, stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo desde el cual cargar la imagen. |

### Ver también
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
