---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο στιγμιότυπο Watermarker με τη συγκεκριμένη διαδρομή εγγράφου."
type: docs
url: /el/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Αρχικοποιεί ένα νέο στιγμιότυπο Watermarker με τη συγκεκριμένη διαδρομή εγγράφου.

Μάθετε περισσότερα για τη φόρτωση εγγράφων: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή αρχείου για τη φόρτωση του εγγράφου. |

| Εγείρει | Περιγραφή |
| :- | :- |
| `UnsupportedFileTypeException` | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| `InvalidPasswordException` | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker

# Φορτώστε ένα έγγραφο.
watermarker = Watermarker("./document.pdf")
# Χρησιμοποιήστε τις μεθόδους Watermarker για να προσθέσετε, αναζητήσετε ή αφαιρέσετε υδατογραφήματα.

# Αποθηκεύστε το έγγραφο.
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

Αρχικοποιεί ένα νέο στιγμιότυπο Watermarker με τη συγκεκριμένη διαδρομή εγγράφου και επιλογές φόρτωσης.

Μάθετε περισσότερα για τη φόρτωση εγγράφων: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή αρχείου για τη φόρτωση του εγγράφου. |
| options | `LoadOptions` | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |

| Εγείρει | Περιγραφή |
| :- | :- |
| `UnsupportedFileTypeException` | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| `InvalidPasswordException` | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # εκτελέστε λειτουργίες στο κρυπτογραφημένο PDF
    pass
```

## __init__ {#file_path-settings}

Αρχικοποιεί ένα Watermarker με τη συγκεκριμένη διαδρομή εγγράφου και ρυθμίσεις.

Μάθετε περισσότερα για τη φόρτωση εγγράφων: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή αρχείου για τη φόρτωση του εγγράφου. |
| settings | `WatermarkerSettings` | Πρόσθετες ρυθμίσεις για χρήση όταν εργάζεστε με το φορτωμένο έγγραφο. |

| Εγείρει | Περιγραφή |
| :- | :- |
| `UnsupportedFileTypeException` | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| `InvalidPasswordException` | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Παράδειγμα

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
    # εργαστείτε με το watermarker, π.χ., αναζητήστε ή αφαιρέστε υδατογραφήματα
    pass
```

## __init__ {#file_path-options-settings}

Αρχικοποιεί ένα νέο στιγμιότυπο Watermarker με τη συγκεκριμένη διαδρομή εγγράφου, επιλογές φόρτωσης και ρυθμίσεις.

Μάθετε περισσότερα για τη φόρτωση εγγράφων: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή αρχείου για τη φόρτωση του εγγράφου. |
| options | `LoadOptions` | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |
| settings | `WatermarkerSettings` | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με το φορτωμένο έγγραφο. |

| Εγείρει | Περιγραφή |
| :- | :- |
| `UnsupportedFileTypeException` | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| `InvalidPasswordException` | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Παράδειγμα

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

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Watermarker με το συγκεκριμένο ρεύμα δεδομένων.

Μάθετε περισσότερα για τη φόρτωση εγγράφων: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή για τη φόρτωση του εγγράφου. |

| Εγείρει | Περιγραφή |
| :- | :- |
| `UnsupportedFileTypeException` | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| `InvalidPasswordException` | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # Χρησιμοποιήστε τις μεθόδους του Watermarker για να προσθέσετε, αναζητήσετε ή αφαιρέσετε υδατογραφήματα.
            watermarker.save(output_stream)
```

## __init__ {#document-options}

Αρχικοποιεί ένα νέο στιγμιότυπο Watermarker με το συγκεκριμένο ρεύμα δεδομένων και επιλογές φόρτωσης.

Μάθετε περισσότερα για τη φόρτωση εγγράφων.

```python
def __init__(self, document, options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή για τη φόρτωση του εγγράφου. |
| options | `LoadOptions` | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |

| Εγείρει | Περιγραφή |
| :- | :- |
| `UnsupportedFileTypeException` | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| `InvalidPasswordException` | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # εκτελέστε λειτουργίες με το watermarker
        pass
```

## __init__ {#document-settings}

Αρχικοποιεί ένα νέο στιγμιότυπο Watermarker με το συγκεκριμένο ρεύμα δεδομένων και ρυθμίσεις.

Μάθετε περισσότερα για τη φόρτωση εγγράφων.

```python
def __init__(self, document, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή για τη φόρτωση του εγγράφου. |
| settings | `WatermarkerSettings` | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με το φορτωμένο έγγραφο. |

| Εγείρει | Περιγραφή |
| :- | :- |
| `UnsupportedFileTypeException` | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| `InvalidPasswordException` | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Παράδειγμα

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
            # εργαστείτε με τα βρεθέντα υδατογραφήματα
```

## __init__ {#document-options-settings}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) με το συγκεκριμένο ρεύμα δεδομένων, επιλογές φόρτωσης και ρυθμίσεις.

Μάθετε περισσότερα για τη φόρτωση εγγράφων στο https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή για τη φόρτωση του εγγράφου. |
| options | `LoadOptions` | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση ενός εγγράφου. |
| settings | `WatermarkerSettings` | Πρόσθετες ρυθμίσεις για χρήση όταν εργάζεστε με το φορτωμένο έγγραφο. |

| Εγείρει | Περιγραφή |
| :- | :- |
| `UnsupportedFileTypeException` | Ο παρεχόμενος τύπος εγγράφου δεν υποστηρίζεται. |
| `InvalidPasswordException` | Ο παρεχόμενος κωδικός πρόσβασης είναι λανθασμένος. |

### Παράδειγμα

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

### Δείτε επίσης
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
