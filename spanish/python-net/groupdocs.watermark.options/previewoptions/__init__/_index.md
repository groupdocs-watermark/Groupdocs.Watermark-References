---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de PreviewOptions que cierra el flujo de salida después de su uso."
type: docs
url: /es/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Inicializa una nueva instancia de PreviewOptions que cierra el flujo de salida después de su uso.

```python
def __init__(self, create_page_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – Crea un flujo para una vista previa de una página específica. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Proporcione un flujo de archivo escribible para cada página a renderizar
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

## __init__ {#create_page_stream-release_page_stream}

Inicializa una nueva instancia de PreviewOptions que devuelve el flujo de salida al cliente para su uso posterior.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable que crea un flujo para una vista previa de una página específica. Recibe el número de página (`int`) y debe devolver un flujo escribible (`io.RawIOBase`). |
| release_page_stream | `ReleasePageStream` | Callable que se invoca cuando la generación de la vista previa de la página está completa y proporciona el flujo de salida. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Proporcione un flujo de archivo escribible para cada página a renderizar
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### Ver también
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
