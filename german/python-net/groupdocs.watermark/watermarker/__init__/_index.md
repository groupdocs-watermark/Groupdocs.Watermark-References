---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Watermarker-Instanz mit dem angegebenen Dokumentpfad."
type: docs
url: /de/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initialisiert eine neue Watermarker-Instanz mit dem angegebenen Dokumentpfad.

Erfahren Sie mehr über das Laden von Dokumenten: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateipfad, von dem das Dokument geladen wird. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `UnsupportedFileTypeException` | Der angegebene Dokumenttyp wird nicht unterstützt. |
| `InvalidPasswordException` | Das angegebene Passwort ist falsch. |

### Beispiel

```python
from groupdocs.watermark import Watermarker

# Laden Sie ein Dokument.
watermarker = Watermarker("./document.pdf")
# Verwenden Sie Watermarker-Methoden, um Wasserzeichen hinzuzufügen, zu suchen oder zu entfernen.

# Speichern Sie das Dokument.
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

Initialisiert eine neue Watermarker-Instanz mit dem angegebenen Dokumentpfad und Ladeoptionen.

Erfahren Sie mehr über das Laden von Dokumenten: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateipfad, von dem das Dokument geladen wird. |
| options | `LoadOptions` | Zusätzliche Optionen, die beim Laden eines Dokuments verwendet werden können. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `UnsupportedFileTypeException` | Der angegebene Dokumenttyp wird nicht unterstützt. |
| `InvalidPasswordException` | Das angegebene Passwort ist falsch. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # Operationen am verschlüsselten PDF ausführen.
    pass
```

## __init__ {#file_path-settings}

Initialisiert einen Watermarker mit dem angegebenen Dokumentpfad und Einstellungen.

Erfahren Sie mehr über das Laden von Dokumenten: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateipfad, von dem das Dokument geladen wird. |
| settings | `WatermarkerSettings` | Zusätzliche Einstellungen, die bei der Arbeit mit dem geladenen Dokument verwendet werden können. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `UnsupportedFileTypeException` | Der angegebene Dokumenttyp wird nicht unterstützt. |
| `InvalidPasswordException` | Das angegebene Passwort ist falsch. |

### Beispiel

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
    # Arbeiten Sie mit Watermarker, z. B. zum Suchen oder Entfernen von Wasserzeichen.
    pass
```

## __init__ {#file_path-options-settings}

Initialisiert eine neue Watermarker-Instanz mit dem angegebenen Dokumentpfad, Ladeoptionen und Einstellungen.

Erfahren Sie mehr über das Laden von Dokumenten: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateipfad, von dem das Dokument geladen wird. |
| options | `LoadOptions` | Zusätzliche Optionen, die beim Laden eines Dokuments verwendet werden können. |
| settings | `WatermarkerSettings` | Zusätzliche Einstellungen, die bei der Arbeit mit geladenen Dokumenten verwendet werden. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `UnsupportedFileTypeException` | Der angegebene Dokumenttyp wird nicht unterstützt. |
| `InvalidPasswordException` | Das angegebene Passwort ist falsch. |

### Beispiel

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

Initialisiert eine neue Instanz der Watermarker-Klasse mit dem angegebenen Stream.

Erfahren Sie mehr über das Laden von Dokumenten: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Stream, von dem das Dokument geladen wird. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `UnsupportedFileTypeException` | Der angegebene Dokumenttyp wird nicht unterstützt. |
| `InvalidPasswordException` | Das angegebene Passwort ist falsch. |

### Beispiel

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # Verwenden Sie Methoden von Watermarker, um Wasserzeichen hinzuzufügen, zu suchen oder zu entfernen.
            watermarker.save(output_stream)
```

## __init__ {#document-options}

Initialisiert eine neue Watermarker-Instanz mit dem angegebenen Stream und Ladeoptionen.

Erfahren Sie mehr über das Laden von Dokumenten.

```python
def __init__(self, document, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Stream, von dem das Dokument geladen wird. |
| options | `LoadOptions` | Zusätzliche Optionen, die beim Laden eines Dokuments verwendet werden können. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `UnsupportedFileTypeException` | Der angegebene Dokumenttyp wird nicht unterstützt. |
| `InvalidPasswordException` | Das angegebene Passwort ist falsch. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # Operationen mit Watermarker ausführen.
        pass
```

## __init__ {#document-settings}

Initialisiert eine neue Watermarker-Instanz mit dem angegebenen Stream und Einstellungen.

Erfahren Sie mehr über das Laden von Dokumenten.

```python
def __init__(self, document, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Stream, von dem das Dokument geladen wird. |
| settings | `WatermarkerSettings` | Zusätzliche Einstellungen, die bei der Arbeit mit geladenen Dokumenten verwendet werden. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `UnsupportedFileTypeException` | Der angegebene Dokumenttyp wird nicht unterstützt. |
| `InvalidPasswordException` | Das angegebene Passwort ist falsch. |

### Beispiel

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
            # mit gefundenen Wasserzeichen arbeiten
```

## __init__ {#document-options-settings}

Initialisiert eine neue Instanz der [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) Klasse mit dem angegebenen Stream, Ladeoptionen und Einstellungen.

Erfahren Sie mehr über das Laden von Dokumenten unter https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options, settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Stream, aus dem das Dokument geladen wird. |
| options | `LoadOptions` | Zusätzliche Optionen, die beim Laden eines Dokuments verwendet werden können. |
| settings | `WatermarkerSettings` | Zusätzliche Einstellungen, die bei der Arbeit mit dem geladenen Dokument verwendet werden können. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `UnsupportedFileTypeException` | Der angegebene Dokumenttyp wird nicht unterstützt. |
| `InvalidPasswordException` | Das angegebene Passwort ist falsch. |

### Beispiel

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

### Siehe auch
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
