---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes a new Watermarker instance with the specified document path."
type: docs
url: /python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initializes a new Watermarker instance with the specified document path.

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

with gw.Watermarker("D:\\input.pdf") as watermarker:
    # Use methods of Watermarker to add, search or remove watermarks.
    watermarker.save("D:\\output.pdf")
```

## __init__ {#file_path-options}

Initializes a new Watermarker instance with the specified document path and load options.

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
    # work with the watermarker instance
    pass
```

## __init__ {#file_path-settings}

Initializes a new Watermarker instance with the specified document path and settings.

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

with gw.Watermarker("document.pdf") as watermarker:
    # Perform operations such as searching for watermarks
    pass
```

## __init__ {#file_path-options-settings}

Initializes a new Watermarker with the specified document path, load options, and settings.

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
import groupdocs.watermark.search.searchcriteria as gws_sc

settings = gw.WatermarkerSettings()
settings.searchable_objects.email_searchable_objects = (
    gw.EmailSearchableObjects.Subject |
    gw.EmailSearchableObjects.HtmlBody |
    gw.EmailSearchableObjects.PlainTextBody
)

load_options = gw.EmailLoadOptions()
with gw.Watermarker(r"D:\\test.msg", load_options, settings) as watermarker:
    criteria = gws_sc.TextSearchCriteria("test", False)
    watermarks = watermarker.search(criteria)
    watermarks.clear()
    watermarker.save()
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

### Example

```python
import io
import groupdocs.watermark as gw

with open("D:/input.pdf", "rb") as input_stream, open("D:/output.pdf", "wb") as output_stream:
    with gw.Watermarker(input_stream) as watermarker:
        # Use methods of Watermarker to add, search, or remove watermarks.
        watermarker.save(output_stream)
```

## __init__ {#document-options}

Initializes a new instance of the Watermarker class with the specified stream and load options.

Learn more about loading documents at https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The stream to load document from. |
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
        # work with the watermarker
        pass
```

## __init__ {#document-settings}

Initializes a new instance of the Watermarker class with the specified stream and settings.

Learn more about loading documents.

```python
def __init__(self, document, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The stream to load document from. |
| settings | `WatermarkerSettings` | Additional settings to use when working with loaded document. |

| Raises | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Supplied document type is not supported. |
| `InvalidPasswordException` | Supplied password is incorrect. |

### Example

```python
import io
import groupdocs.watermark as gw
from groupdocs.watermark import (
    WatermarkerSettings,
    SearchableObjects,
    WordProcessingSearchableObjects,
    SpreadsheetSearchableObjects,
    PresentationSearchableObjects,
    DiagramSearchableObjects,
    PdfSearchableObjects,
)

# Configure global searchable objects
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

# Process multiple files
for file_path in ["doc1.pdf", "doc2.docx"]:
    with open(file_path, "rb") as stream:
        with gw.Watermarker(stream, settings) as watermarker:
            # work with watermarker, e.g., search or add watermarks
            pass
```

## __init__ {#document-options-settings}

Initializes a new Watermarker instance with the specified document stream, load options, and settings.

Learn more about loading documents: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The stream to load the document from. |
| options | `LoadOptions` | Additional options to use when loading a document. |
| settings | `WatermarkerSettings` | Additional settings to use when working with the loaded document. |

| Raises | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Supplied document type is not supported. |
| `InvalidPasswordException` | Supplied password is incorrect. |

### Example

```python
import groupdocs.watermark as gw

# Configure searchable objects for email documents
settings = gw.WatermarkerSettings()
settings.searchable_objects = gw.SearchableObjects(
    email_searchable_objects=gw.EmailSearchableObjects.Subject
    | gw.EmailSearchableObjects.HtmlBody
    | gw.EmailSearchableObjects.PlainTextBody
)

load_options = gw.EmailLoadOptions()

with open(r"D:\test.msg", "rb") as stream:
    with gw.Watermarker(stream, load_options, settings) as watermarker:
        criteria = gw.TextSearchCriteria("test", False)
        watermarks = watermarker.search(criteria)
        watermarks.clear()  # Remove found text fragments
        watermarker.save()
```

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
