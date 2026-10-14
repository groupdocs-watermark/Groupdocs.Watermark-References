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
from groupdocs.watermark import Watermarker

# Load a document.
watermarker = Watermarker("./document.pdf")
# Use Watermarker methods to add, search, or remove watermarks.

# Save the document.
watermarker.save("./output.pdf")
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
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # perform operations on the encrypted PDF
    pass
```

## __init__ {#file_path-settings}

Initializes a Watermarker with the specified document path and settings.

Learn more about loading documents: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to load document from. |
| settings | `WatermarkerSettings` | Additional settings to use when working with the loaded document. |

| Raises | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Supplied document type is not supported. |
| `InvalidPasswordException` | Supplied password is incorrect. |

### Example

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
    # work with watermarker, e.g., search or remove watermarks
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

Initializes a new instance of the Watermarker class with the specified stream.

Learn more about loading documents: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

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
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # Use methods of Watermarker to add, search or remove watermarks.
            watermarker.save(output_stream)
```

## __init__ {#document-options}

Initializes a new Watermarker instance with the specified stream and load options.

Learn more about loading documents.

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
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # perform operations with watermarker
        pass
```

## __init__ {#document-settings}

Initializes a new Watermarker instance with the specified stream and settings.

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
            # work with found watermarks
```

## __init__ {#document-options-settings}

Initializes a new instance of the [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) class with the specified stream, load options and settings.

Learn more about loading documents at https://docs.groupdocs.com/display/watermarknet/Loading+documents.

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

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
