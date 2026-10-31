---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de Watermarker avec le chemin de document spécifié."
type: docs
url: /fr/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initialise une nouvelle instance de Watermarker avec le chemin de document spécifié.

En savoir plus sur le chargement des documents : https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier à partir duquel charger le document. |

| Lève | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Le type de document fourni n'est pas pris en charge. |
| `InvalidPasswordException` | Le mot de passe fourni est incorrect. |

### Exemple

```python
from groupdocs.watermark import Watermarker

# Charger un document.
watermarker = Watermarker("./document.pdf")
# Utilisez les méthodes de Watermarker pour ajouter, rechercher ou supprimer des filigranes.

# Enregistrez le document.
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

Initialise une nouvelle instance de Watermarker avec le chemin de document spécifié et les options de chargement.

En savoir plus sur le chargement des documents : https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier à partir duquel charger le document. |
| options | `LoadOptions` | Options supplémentaires à utiliser lors du chargement d'un document. |

| Lève | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Le type de document fourni n'est pas pris en charge. |
| `InvalidPasswordException` | Le mot de passe fourni est incorrect. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # effectuer des opérations sur le PDF chiffré
    pass
```

## __init__ {#file_path-settings}

Initialise un Watermarker avec le chemin de document spécifié et les paramètres.

En savoir plus sur le chargement des documents : https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier à partir duquel charger le document. |
| settings | `WatermarkerSettings` | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |

| Lève | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Le type de document fourni n'est pas pris en charge. |
| `InvalidPasswordException` | Le mot de passe fourni est incorrect. |

### Exemple

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
    # travailler avec watermarker, par ex., rechercher ou supprimer des filigranes
    pass
```

## __init__ {#file_path-options-settings}

Initialise une nouvelle instance de Watermarker avec le chemin de document spécifié, les options de chargement et les paramètres.

En savoir plus sur le chargement des documents : https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier à partir duquel charger le document. |
| options | `LoadOptions` | Options supplémentaires à utiliser lors du chargement d'un document. |
| settings | `WatermarkerSettings` | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |

| Lève | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Le type de document fourni n'est pas pris en charge. |
| `InvalidPasswordException` | Le mot de passe fourni est incorrect. |

### Exemple

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

Initialise une nouvelle instance de la classe Watermarker avec le flux spécifié.

En savoir plus sur le chargement des documents : https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux à partir duquel charger le document. |

| Lève | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Le type de document fourni n'est pas pris en charge. |
| `InvalidPasswordException` | Le mot de passe fourni est incorrect. |

### Exemple

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # Utilisez les méthodes de Watermarker pour ajouter, rechercher ou supprimer des filigranes.
            watermarker.save(output_stream)
```

## __init__ {#document-options}

Initialise une nouvelle instance de Watermarker avec le flux spécifié et les options de chargement.

En savoir plus sur le chargement des documents.

```python
def __init__(self, document, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux à partir duquel charger le document. |
| options | `LoadOptions` | Options supplémentaires à utiliser lors du chargement d'un document. |

| Lève | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Le type de document fourni n'est pas pris en charge. |
| `InvalidPasswordException` | Le mot de passe fourni est incorrect. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # effectuer des opérations avec watermarker
        pass
```

## __init__ {#document-settings}

Initialise une nouvelle instance de Watermarker avec le flux spécifié et les paramètres.

En savoir plus sur le chargement des documents.

```python
def __init__(self, document, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux à partir duquel charger le document. |
| settings | `WatermarkerSettings` | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |

| Lève | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Le type de document fourni n'est pas pris en charge. |
| `InvalidPasswordException` | Le mot de passe fourni est incorrect. |

### Exemple

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
            # travailler avec les filigranes trouvés
```

## __init__ {#document-options-settings}

Initialise une nouvelle instance de la classe [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) avec le flux spécifié, les options de chargement et les paramètres.

En savoir plus sur le chargement des documents à https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux à partir duquel charger le document. |
| options | `LoadOptions` | Options supplémentaires à utiliser lors du chargement d'un document. |
| settings | `WatermarkerSettings` | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |

| Lève | Description |
| :- | :- |
| `UnsupportedFileTypeException` | Le type de document fourni n'est pas pris en charge. |
| `InvalidPasswordException` | Le mot de passe fourni est incorrect. |

### Exemple

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

### Voir aussi
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
