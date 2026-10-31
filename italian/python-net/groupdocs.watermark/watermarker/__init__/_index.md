---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza di Watermarker con il percorso del documento specificato."
type: docs
url: /it/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Inizializza una nuova istanza di Watermarker con il percorso del documento specificato.

Scopri di più sul caricamento dei documenti: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file da cui caricare il documento. |

| Genera | Descrizione |
| :- | :- |
| `UnsupportedFileTypeException` | Il tipo di documento fornito non è supportato. |
| `InvalidPasswordException` | La password fornita è errata. |

### Esempio

```python
from groupdocs.watermark import Watermarker

# Carica un documento.
watermarker = Watermarker("./document.pdf")
# Usa i metodi di Watermarker per aggiungere, cercare o rimuovere filigrane.

# Salva il documento.
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

Inizializza una nuova istanza di Watermarker con il percorso del documento specificato e le opzioni di caricamento.

Scopri di più sul caricamento dei documenti: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file da cui caricare il documento. |
| options | `LoadOptions` | Opzioni aggiuntive da usare durante il caricamento di un documento. |

| Genera | Descrizione |
| :- | :- |
| `UnsupportedFileTypeException` | Il tipo di documento fornito non è supportato. |
| `InvalidPasswordException` | La password fornita è errata. |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # eseguire operazioni sul PDF crittografato
    pass
```

## __init__ {#file_path-settings}

Inizializza un Watermarker con il percorso del documento specificato e le impostazioni.

Scopri di più sul caricamento dei documenti: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file da cui caricare il documento. |
| settings | `WatermarkerSettings` | Impostazioni aggiuntive da usare quando si lavora con il documento caricato. |

| Genera | Descrizione |
| :- | :- |
| `UnsupportedFileTypeException` | Il tipo di documento fornito non è supportato. |
| `InvalidPasswordException` | La password fornita è errata. |

### Esempio

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
    # lavorare con watermarker, ad esempio cercare o rimuovere filigrane
    pass
```

## __init__ {#file_path-options-settings}

Inizializza una nuova istanza di Watermarker con il percorso del documento specificato, le opzioni di caricamento e le impostazioni.

Scopri di più sul caricamento dei documenti: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file da cui caricare il documento. |
| options | `LoadOptions` | Opzioni aggiuntive da usare durante il caricamento di un documento. |
| settings | `WatermarkerSettings` | Impostazioni aggiuntive da utilizzare quando si lavora con il documento caricato. |

| Genera | Descrizione |
| :- | :- |
| `UnsupportedFileTypeException` | Il tipo di documento fornito non è supportato. |
| `InvalidPasswordException` | La password fornita è errata. |

### Esempio

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

Inizializza una nuova istanza della classe Watermarker con lo stream specificato.

Scopri di più sul caricamento dei documenti: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Lo stream da cui caricare il documento. |

| Genera | Descrizione |
| :- | :- |
| `UnsupportedFileTypeException` | Il tipo di documento fornito non è supportato. |
| `InvalidPasswordException` | La password fornita è errata. |

### Esempio

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # Usa i metodi di Watermarker per aggiungere, cercare o rimuovere filigrane.
            watermarker.save(output_stream)
```

## __init__ {#document-options}

Inizializza una nuova istanza di Watermarker con lo stream specificato e le opzioni di caricamento.

Scopri di più sul caricamento dei documenti.

```python
def __init__(self, document, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Lo stream da cui caricare il documento. |
| options | `LoadOptions` | Opzioni aggiuntive da usare durante il caricamento di un documento. |

| Genera | Descrizione |
| :- | :- |
| `UnsupportedFileTypeException` | Il tipo di documento fornito non è supportato. |
| `InvalidPasswordException` | La password fornita è errata. |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # eseguire operazioni con watermarker
        pass
```

## __init__ {#document-settings}

Inizializza una nuova istanza di Watermarker con lo stream specificato e le impostazioni.

Scopri di più sul caricamento dei documenti.

```python
def __init__(self, document, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Lo stream da cui caricare il documento. |
| settings | `WatermarkerSettings` | Impostazioni aggiuntive da utilizzare quando si lavora con il documento caricato. |

| Genera | Descrizione |
| :- | :- |
| `UnsupportedFileTypeException` | Il tipo di documento fornito non è supportato. |
| `InvalidPasswordException` | La password fornita è errata. |

### Esempio

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
            # lavorare con le filigrane trovate
```

## __init__ {#document-options-settings}

Inizializza una nuova istanza della classe [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) con lo stream specificato, le opzioni di caricamento e le impostazioni.

Scopri di più sul caricamento dei documenti su https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options, settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Lo stream da cui caricare il documento. |
| options | `LoadOptions` | Opzioni aggiuntive da usare durante il caricamento di un documento. |
| settings | `WatermarkerSettings` | Impostazioni aggiuntive da usare quando si lavora con il documento caricato. |

| Genera | Descrizione |
| :- | :- |
| `UnsupportedFileTypeException` | Il tipo di documento fornito non è supportato. |
| `InvalidPasswordException` | La password fornita è errata. |

### Esempio

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

### Vedi anche
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
