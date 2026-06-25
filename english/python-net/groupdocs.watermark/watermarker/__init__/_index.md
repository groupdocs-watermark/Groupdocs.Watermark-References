---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initializes a new instance of Watermarker with the specified document path.

Learn more about loading documents: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to load the document from. |

| Raises | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Supplied document type is not supported. |
| `InvalidPasswordException` | Supplied password is incorrect. |

### Example

```python
import groupdocs.watermark as gw

with gw.Watermarker("input.pdf") as watermarker:
    # Use methods of Watermarker to add, search, or remove watermarks.
    watermarker.save("output.pdf")
```

## __init__ {#file_path-options}

Initializes a new Watermarker with the specified document path and load options.

Learn more about loading documents: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to load document from. |
| options | `LoadOptions` | Additional options to use when loading a document. |

| Raises | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Supplied document type is not supported. |
| `InvalidPasswordException` | Supplied password is incorrect. |

### Example

```python
import groupdocs.watermark as gw

load_options = gw.PdfLoadOptions()
load_options.password = "123"
with gw.Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # ...
    pass
```

## __init__ {#file_path-settings}

Initializes a new Watermarker instance with the specified document path and optional settings.

Learn more about loading documents: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to load document from. |
| settings | `WatermarkerSettings` | Additional settings to use when working with loaded document. |

| Raises | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Supplied document type is not supported. |
| `InvalidPasswordException` | Supplied password is incorrect. |

### Example

```python
import groupdocs.watermark as gw

# Load a PDF document
with gw.Watermarker("document.pdf") as watermarker:
    # Perform operations, e.g., search for watermarks
    pass
```

## __init__ {#file_path-options-settings}

Initializes a new Watermarker instance with the specified document path, load options, and settings.

Learn more about loading documents: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to load document from. |
| options | `LoadOptions` | Additional options to use when loading a document. |
| settings | `WatermarkerSettings` | Additional settings to use when working with loaded document. |

| Raises | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Supplied document type is not supported. |
| `InvalidPasswordException` | Supplied password is incorrect. |

### Example

```python
import groupdocs.watermark as gw

load_options = gw.PdfLoadOptions()
settings = gw.WatermarkerSettings()
with gw.Watermarker("document.pdf", load_options, settings) as watermarker:
    # perform operations, e.g., search, modify, or save the document
    pass
```

## __init__ {#document}

Initializes a new Watermarker instance with the specified stream.

Learn more about loading documents.

```python
def __init__(self, document):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The stream to load document from. |

| Raises | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Supplied document type is not supported. |
| `InvalidPasswordException` | Supplied password is incorrect. |

## __init__ {#document-options}

Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) class with the specified stream and load options.

Learn more about loading documents at https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The stream to load the document from (`io.RawIOBase`). |
| options | `LoadOptions` | Additional options to use when loading a document. |

| Raises | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Supplied document type is not supported. |
| `InvalidPasswordException` | Supplied password is incorrect. |

### Example

```python
import groupdocs.watermark as gw

load_options = gw.PdfLoadOptions()
load_options.password = "123"

with open(r"C:\Documents\test.pdf", "rb") as stream:
    with gw.Watermarker(stream, load_options) as watermarker:
        # Perform operations with the watermarker
        pass
```

## __init__ {#document-settings}

Initializes a new Watermarker instance with the given document stream and optional settings.

Learn more about loading documents: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The stream to load the document from. |
| settings | `WatermarkerSettings` | Additional settings to use when working with the loaded document. |

| Raises | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Supplied document type is not supported. |
| `InvalidPasswordException` | Supplied password is incorrect. |

### Example

```python
import groupdocs.watermark as gw
from groupdocs.watermark import WatermarkerSettings, SearchableObjects
from groupdocs.watermark.contents import (
    WordProcessingSearchableObjects,
    SpreadsheetSearchableObjects,
    PresentationSearchableObjects,
    DiagramSearchableObjects,
    PdfSearchableObjects,
)

# Configure searchable objects globally
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

# Load a document from a file stream
with open("example.pdf", "rb") as stream:
    with gw.Watermarker(stream, settings) as watermarker:
        # Work with the watermarker instance here
        pass
```

## __init__ {#document-options-settings}

Initializes a new Watermarker instance with the given document stream, load options, and settings.

Learn more about loading documents.

```python
def __init__(self, document, options, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The stream to load document from. |
| options | `LoadOptions` | Additional options to use when loading a document. |
| settings | `WatermarkerSettings` | Additional settings to use when working with loaded document. |

| Raises | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Supplied document type is not supported. |
| `InvalidPasswordException` | Supplied password is incorrect. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf

load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    pdf_content = watermarker.get_content(gwc_pdf.PdfContent)
    print(pdf_content.pages[0].width)
    print(pdf_content.pages[0].height)
```

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
