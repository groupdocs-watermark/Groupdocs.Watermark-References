---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny Watermarker-instans med den angivna dokumentvägen."
type: docs
url: /sv/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initierar en ny Watermarker-instans med den angivna dokumentvägen.

Läs mer om att ladda dokument: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filvägen att ladda dokumentet från. |

| Kastar | Beskrivning |
| :- | :- |
| `UnsupportedFileTypeException` | Den angivna dokumenttypen stöds inte. |
| `InvalidPasswordException` | Angivet lösenord är felaktigt. |

### Exempel

```python
from groupdocs.watermark import Watermarker

# Läs in ett dokument.
watermarker = Watermarker("./document.pdf")
# Använd Watermarker-metoder för att lägga till, söka eller ta bort vattenmärken.

# Spara dokumentet.
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

Initierar en ny Watermarker-instans med den angivna dokumentvägen och inläsningsalternativ.

Läs mer om att ladda dokument: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filvägen att läsa in dokumentet från. |
| options | `LoadOptions` | Ytterligare alternativ att använda när du läser in ett dokument. |

| Kastar | Beskrivning |
| :- | :- |
| `UnsupportedFileTypeException` | Den angivna dokumenttypen stöds inte. |
| `InvalidPasswordException` | Angivet lösenord är felaktigt. |

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # utför operationer på den krypterade PDF-filen
    pass
```

## __init__ {#file_path-settings}

Initierar en Watermarker med den angivna dokumentvägen och inställningarna.

Läs mer om att ladda dokument: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filvägen att läsa in dokumentet från. |
| settings | `WatermarkerSettings` | Ytterligare inställningar att använda när du arbetar med det inlästa dokumentet. |

| Kastar | Beskrivning |
| :- | :- |
| `UnsupportedFileTypeException` | Den angivna dokumenttypen stöds inte. |
| `InvalidPasswordException` | Angivet lösenord är felaktigt. |

### Exempel

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
    # arbeta med watermarker, t.ex. söka eller ta bort vattenmärken
    pass
```

## __init__ {#file_path-options-settings}

Initierar en ny Watermarker-instans med den angivna dokumentvägen, inläsningsalternativ och inställningar.

Läs mer om att ladda dokument: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filvägen att läsa in dokumentet från. |
| options | `LoadOptions` | Ytterligare alternativ att använda när du läser in ett dokument. |
| settings | `WatermarkerSettings` | Ytterligare inställningar att använda när du arbetar med ett inläst dokument. |

| Kastar | Beskrivning |
| :- | :- |
| `UnsupportedFileTypeException` | Den angivna dokumenttypen stöds inte. |
| `InvalidPasswordException` | Angivet lösenord är felaktigt. |

### Exempel

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

Initierar en ny instans av Watermarker-klassen med den angivna strömmen.

Läs mer om att ladda dokument: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Strömmen att läsa in dokumentet från. |

| Kastar | Beskrivning |
| :- | :- |
| `UnsupportedFileTypeException` | Den angivna dokumenttypen stöds inte. |
| `InvalidPasswordException` | Angivet lösenord är felaktigt. |

### Exempel

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # Använd metoderna i Watermarker för att lägga till, söka eller ta bort vattenmärken.
            watermarker.save(output_stream)
```

## __init__ {#document-options}

Initierar en ny Watermarker-instans med den angivna strömmen och inläsningsalternativ.

Läs mer om att läsa in dokument.

```python
def __init__(self, document, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Strömmen att läsa in dokumentet från. |
| options | `LoadOptions` | Ytterligare alternativ att använda när du läser in ett dokument. |

| Kastar | Beskrivning |
| :- | :- |
| `UnsupportedFileTypeException` | Den angivna dokumenttypen stöds inte. |
| `InvalidPasswordException` | Angivet lösenord är felaktigt. |

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # utför operationer med watermarker
        pass
```

## __init__ {#document-settings}

Initierar en ny Watermarker-instans med den angivna strömmen och inställningarna.

Läs mer om att läsa in dokument.

```python
def __init__(self, document, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Strömmen att läsa in dokumentet från. |
| settings | `WatermarkerSettings` | Ytterligare inställningar att använda när du arbetar med ett inläst dokument. |

| Kastar | Beskrivning |
| :- | :- |
| `UnsupportedFileTypeException` | Den angivna dokumenttypen stöds inte. |
| `InvalidPasswordException` | Angivet lösenord är felaktigt. |

### Exempel

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
            # arbeta med hittade vattenmärken
```

## __init__ {#document-options-settings}

Initierar en ny instans av [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) klassen med den angivna strömmen, inläsningsalternativ och inställningar.

Läs mer om att läsa in dokument på https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Strömmen att läsa in dokumentet från. |
| options | `LoadOptions` | Ytterligare alternativ att använda när du läser in ett dokument. |
| settings | `WatermarkerSettings` | Ytterligare inställningar att använda när du arbetar med det inlästa dokumentet. |

| Kastar | Beskrivning |
| :- | :- |
| `UnsupportedFileTypeException` | Den angivna dokumenttypen stöds inte. |
| `InvalidPasswordException` | Angivet lösenord är felaktigt. |

### Exempel

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

### Se även
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
