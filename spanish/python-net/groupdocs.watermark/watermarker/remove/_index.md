---
title: "método remove"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Elimina una marca de agua del documento."
type: docs
url: /es/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

Elimina una marca de agua del documento.

Obtenga más información sobre la eliminación de marcas de agua: Eliminación de marcas de agua encontradas.

```python
def remove(self, possible_watermark):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | La marca de agua a eliminar. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker

def remove_first_watermark():
    with Watermarker("./document.pdf") as watermarker:
        watermarks = watermarker.search()
        if watermarks:
            watermarker.remove(watermarks[0])
        watermarker.save("./output.pdf")
```

## remove {#possible_watermarks}

Elimina todas las marcas de agua de la colección del documento.

Obtenga más información sobre la eliminación de marcas de agua en la documentación de GroupDocs.

```python
def remove(self, possible_watermarks):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | La colección de marcas de agua a eliminar. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # Eliminar en orden inverso para mantener los índices válidos
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### Ver también
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
