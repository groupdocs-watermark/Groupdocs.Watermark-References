---
title: "método save"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Guarda los datos del documento en el flujo subyacente."
type: docs
url: /es/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

Guarda los datos del documento en el flujo subyacente.

Obtenga más información sobre guardar los documentos: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker(r"D:\\test.msg") as watermarker:
    criteria = TextSearchCriteria("test", False)
    watermarks = watermarker.search(criteria)
    watermarker.remove(watermarks)
    watermarker.save()
```

## save {#file_path}

Guarda el documento en la ubicación de archivo especificada.

Obtenga más información sobre guardar los documentos: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo donde guardar los datos del documento. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

def add_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)
        watermarker.save("output.pdf")
```

## save {#document}

Guarda el documento en el flujo especificado.

Obtenga más información sobre guardar los documentos en https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, document):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo donde guardar los datos del documento. |

### Ejemplo

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    stream = BytesIO()
    watermarker.save(stream)
    # `stream` ahora contiene los bytes PDF guardados
```

## save {#options}

Guarda los datos del documento en el flujo subyacente usando opciones de guardado.

Obtenga más información sobre guardar los documentos.

```python
def save(self, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | `SaveOptions` | Opciones adicionales para usar al guardar un documento. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save(SaveOptions())
```

## save {#file_path-options}

Guarda el documento en la ubicación de archivo especificada usando opciones de guardado.

Obtenga más información sobre guardar los documentos: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo donde guardar los datos del documento. |
| options | `SaveOptions` | Opciones adicionales para usar al guardar un documento. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font
from groupdocs.watermark.options import SaveOptions

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save("output.pdf", SaveOptions())
```

## save {#document-options}

Guarda el documento en el flujo especificado usando opciones de guardado.

Obtenga más información sobre guardar los documentos en la documentación de GroupDocs.

```python
def save(self, document, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo donde guardar los datos del documento. |
| options | `SaveOptions` | Opciones adicionales para usar al guardar un documento. |

### Ejemplo

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

def add_watermark_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)

        stream = BytesIO()
        watermarker.save(stream, SaveOptions())
        # stream ahora contiene los datos PDF guardados
        # p. ej., escribir en un archivo
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### Ver también
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
