---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw Watermarker‑exemplaar met het opgegeven documentpad."
type: docs
url: /nl/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initialiseert een nieuw Watermarker‑exemplaar met het opgegeven documentpad.

Meer informatie over het laden van documenten: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het bestandspad om het document te laden. |

| Verhoogt | Beschrijving |
| :- | :- |
| `UnsupportedFileTypeException` | Het opgegeven documenttype wordt niet ondersteund. |
| `InvalidPasswordException` | Het opgegeven wachtwoord is onjuist. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker

# Laad een document.
watermarker = Watermarker("./document.pdf")
# Gebruik Watermarker-methoden om watermerken toe te voegen, te zoeken of te verwijderen.

# Sla het document op.
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

Initialiseert een nieuw Watermarker‑exemplaar met het opgegeven documentpad en laadopties.

Meer informatie over het laden van documenten: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het bestandspad om het document te laden. |
| options | `LoadOptions` | Aanvullende opties om te gebruiken bij het laden van een document. |

| Verhoogt | Beschrijving |
| :- | :- |
| `UnsupportedFileTypeException` | Het opgegeven documenttype wordt niet ondersteund. |
| `InvalidPasswordException` | Het opgegeven wachtwoord is onjuist. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # voer bewerkingen uit op de versleutelde PDF
    pass
```

## __init__ {#file_path-settings}

Initialiseert een Watermarker met het opgegeven documentpad en instellingen.

Meer informatie over het laden van documenten: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het bestandspad om het document te laden. |
| settings | `WatermarkerSettings` | Aanvullende instellingen om te gebruiken bij het werken met het geladen document. |

| Verhoogt | Beschrijving |
| :- | :- |
| `UnsupportedFileTypeException` | Het opgegeven documenttype wordt niet ondersteund. |
| `InvalidPasswordException` | Het opgegeven wachtwoord is onjuist. |

### Voorbeeld

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
    # werk met watermarker, bijv., zoek of verwijder watermerken
    pass
```

## __init__ {#file_path-options-settings}

Initialiseert een nieuw Watermarker‑exemplaar met het opgegeven documentpad, laadopties en instellingen.

Meer informatie over het laden van documenten: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het bestandspad om het document te laden. |
| options | `LoadOptions` | Aanvullende opties om te gebruiken bij het laden van een document. |
| settings | `WatermarkerSettings` | Aanvullende instellingen om te gebruiken bij het werken met een geladen document. |

| Verhoogt | Beschrijving |
| :- | :- |
| `UnsupportedFileTypeException` | Het opgegeven documenttype wordt niet ondersteund. |
| `InvalidPasswordException` | Het opgegeven wachtwoord is onjuist. |

### Voorbeeld

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

Initialiseert een nieuw exemplaar van de Watermarker‑klasse met de opgegeven stream.

Meer informatie over het laden van documenten: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De stream om het document te laden. |

| Verhoogt | Beschrijving |
| :- | :- |
| `UnsupportedFileTypeException` | Het opgegeven documenttype wordt niet ondersteund. |
| `InvalidPasswordException` | Het opgegeven wachtwoord is onjuist. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # Gebruik methoden van Watermarker om watermerken toe te voegen, te zoeken of te verwijderen.
            watermarker.save(output_stream)
```

## __init__ {#document-options}

Initialiseert een nieuw Watermarker‑exemplaar met de opgegeven stream en laadopties.

Meer informatie over het laden van documenten.

```python
def __init__(self, document, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De stream om het document te laden. |
| options | `LoadOptions` | Aanvullende opties om te gebruiken bij het laden van een document. |

| Verhoogt | Beschrijving |
| :- | :- |
| `UnsupportedFileTypeException` | Het opgegeven documenttype wordt niet ondersteund. |
| `InvalidPasswordException` | Het opgegeven wachtwoord is onjuist. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # voer bewerkingen uit met watermarker
        pass
```

## __init__ {#document-settings}

Initialiseert een nieuw Watermarker‑exemplaar met de opgegeven stream en instellingen.

Meer informatie over het laden van documenten.

```python
def __init__(self, document, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De stream om het document te laden. |
| settings | `WatermarkerSettings` | Aanvullende instellingen om te gebruiken bij het werken met een geladen document. |

| Verhoogt | Beschrijving |
| :- | :- |
| `UnsupportedFileTypeException` | Het opgegeven documenttype wordt niet ondersteund. |
| `InvalidPasswordException` | Het opgegeven wachtwoord is onjuist. |

### Voorbeeld

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
            # werk met gevonden watermerken
```

## __init__ {#document-options-settings}

Initialiseert een nieuw exemplaar van de [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) klasse met de opgegeven stream, laadopties en instellingen.

Meer informatie over het laden van documenten op https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De stream om het document te laden. |
| options | `LoadOptions` | Aanvullende opties om te gebruiken bij het laden van een document. |
| settings | `WatermarkerSettings` | Aanvullende instellingen om te gebruiken bij het werken met het geladen document. |

| Verhoogt | Beschrijving |
| :- | :- |
| `UnsupportedFileTypeException` | Het opgegeven documenttype wordt niet ondersteund. |
| `InvalidPasswordException` | Het opgegeven wachtwoord is onjuist. |

### Voorbeeld

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

### Zie ook
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
