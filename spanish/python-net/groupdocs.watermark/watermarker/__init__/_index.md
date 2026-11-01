---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de Watermarker con la ruta de documento especificada."
type: docs
url: /es/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Inicializa una nueva instancia de Watermarker con la ruta de documento especificada.

Obtén más información sobre la carga de documentos: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo desde la cual cargar el documento. |

| Lanza | Descripción |
| :- | :- |
| `UnsupportedFileTypeException` | El tipo de documento proporcionado no es compatible. |
| `InvalidPasswordException` | La contraseña proporcionada es incorrecta. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker

# Cargar un documento.
watermarker = Watermarker("./document.pdf")
# Utiliza los métodos de Watermarker para añadir, buscar o eliminar marcas de agua.

# Guardar el documento.
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

Inicializa una nueva instancia de Watermarker con la ruta de documento especificada y opciones de carga.

Obtén más información sobre la carga de documentos: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo desde la cual cargar el documento. |
| options | `LoadOptions` | Opciones adicionales para usar al cargar un documento. |

| Lanza | Descripción |
| :- | :- |
| `UnsupportedFileTypeException` | El tipo de documento proporcionado no es compatible. |
| `InvalidPasswordException` | La contraseña proporcionada es incorrecta. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # realizar operaciones sobre el PDF cifrado
    pass
```

## __init__ {#file_path-settings}

Inicializa un Watermarker con la ruta de documento y la configuración especificadas.

Obtén más información sobre la carga de documentos: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo desde la cual cargar el documento. |
| settings | `WatermarkerSettings` | Configuraciones adicionales para usar al trabajar con el documento cargado. |

| Lanza | Descripción |
| :- | :- |
| `UnsupportedFileTypeException` | El tipo de documento proporcionado no es compatible. |
| `InvalidPasswordException` | La contraseña proporcionada es incorrecta. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import SearchableObjects
from groupdocs.watermark.search.objects import WordProcessingSearchableObjects, SpreadsheetSearchableObjects, PresentationSearchableObjects, DiagramSearchableObjects, PdfSearchableObjects

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
                     | WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=PresentationSearchableObjects.SLIDES_BACKGROUNDS
                  | PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=DiagramSearchableObjects.NONE,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    # trabajar con watermarker, p. ej., buscar o eliminar marcas de agua
    pass
```

## __init__ {#file_path-options-settings}

Inicializa una nueva instancia de Watermarker con la ruta de documento, opciones de carga y configuración especificadas.

Obtén más información sobre la carga de documentos: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo desde la cual cargar el documento. |
| options | `LoadOptions` | Opciones adicionales para usar al cargar un documento. |
| settings | `WatermarkerSettings` | Configuraciones adicionales para usar al trabajar con el documento cargado. |

| Lanza | Descripción |
| :- | :- |
| `UnsupportedFileTypeException` | El tipo de documento proporcionado no es compatible. |
| `InvalidPasswordException` | La contraseña proporcionada es incorrecta. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.options.email import EmailLoadOptions
from groupdocs.watermark.search.search_criteria import TextSearchCriteria
from groupdocs.watermark.search.objects import SearchableObjects, EmailSearchableObjects

def search_email():
    settings = WatermarkerSettings()
    settings.searchable_objects = SearchableObjects(
        email_searchable_objects=(
            EmailSearchableObjects.Subject
            | EmailSearchableObjects.HtmlBody
            | EmailSearchableObjects.PlainTextBody
        )
    )
    load_options = EmailLoadOptions()
    with Watermarker("./test.msg", load_options, settings) as watermarker:
        criteria = TextSearchCriteria("test", False)
        watermarks = watermarker.search(criteria)
        watermarks.clear()
        watermarker.save()
```

## __init__ {#document}

Inicializa una nueva instancia de la clase Watermarker con el flujo especificado.

Obtén más información sobre la carga de documentos: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo desde el cual cargar el documento. |

| Lanza | Descripción |
| :- | :- |
| `UnsupportedFileTypeException` | El tipo de documento proporcionado no es compatible. |
| `InvalidPasswordException` | La contraseña proporcionada es incorrecta. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # Utiliza los métodos de Watermarker para añadir, buscar o eliminar marcas de agua.
            watermarker.save(output_stream)
```

## __init__ {#document-options}

Inicializa una nueva instancia de Watermarker con el flujo especificado y opciones de carga.

Obtén más información sobre la carga de documentos.

```python
def __init__(self, document, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo desde el cual cargar el documento. |
| options | `LoadOptions` | Opciones adicionales para usar al cargar un documento. |

| Lanza | Descripción |
| :- | :- |
| `UnsupportedFileTypeException` | El tipo de documento proporcionado no es compatible. |
| `InvalidPasswordException` | La contraseña proporcionada es incorrecta. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # realizar operaciones con watermarker
        pass
```

## __init__ {#document-settings}

Inicializa una nueva instancia de Watermarker con el flujo especificado y la configuración.

Obtén más información sobre la carga de documentos.

```python
def __init__(self, document, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo desde el cual cargar el documento. |
| settings | `WatermarkerSettings` | Configuraciones adicionales para usar al trabajar con el documento cargado. |

| Lanza | Descripción |
| :- | :- |
| `UnsupportedFileTypeException` | El tipo de documento proporcionado no es compatible. |
| `InvalidPasswordException` | La contraseña proporcionada es incorrecta. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import SearchableObjects
from groupdocs.watermark.search.objects import WordProcessingSearchableObjects, SpreadsheetSearchableObjects, PresentationSearchableObjects, DiagramSearchableObjects, PdfSearchableObjects

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS | WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=PresentationSearchableObjects.SLIDES_BACKGROUNDS | PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=DiagramSearchableObjects.NONE,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

for file_path in ["./document1.pdf", "./document2.docx"]:
    with open(file_path, "rb") as stream:
        with Watermarker(stream, settings) as watermarker:
            watermarks = watermarker.search()
            # trabajar con marcas de agua encontradas
```

## __init__ {#document-options-settings}

Inicializa una nueva instancia de la clase [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) con el flujo especificado, opciones de carga y configuración.

Obtén más información sobre la carga de documentos en https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo desde el cual cargar el documento. |
| options | `LoadOptions` | Opciones adicionales para usar al cargar un documento. |
| settings | `WatermarkerSettings` | Configuraciones adicionales para usar al trabajar con el documento cargado. |

| Lanza | Descripción |
| :- | :- |
| `UnsupportedFileTypeException` | El tipo de documento proporcionado no es compatible. |
| `InvalidPasswordException` | La contraseña proporcionada es incorrecta. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.options.email import EmailLoadOptions
from groupdocs.watermark.search.objects import SearchableObjects, EmailSearchableObjects
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    email_searchable_objects=(
        EmailSearchableObjects.Subject
        | EmailSearchableObjects.HtmlBody
        | EmailSearchableObjects.PlainTextBody
    )
)

load_options = EmailLoadOptions()
with open("./test.msg", "rb") as stream:
    with Watermarker(stream, load_options, settings) as watermarker:
        criteria = TextSearchCriteria("test", False)
        watermarks = watermarker.search(criteria)
        watermarks.clear()
        watermarker.save("./output.msg")
```

### Ver también
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
