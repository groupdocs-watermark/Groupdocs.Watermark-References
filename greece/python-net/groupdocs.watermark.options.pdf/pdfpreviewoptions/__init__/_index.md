---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης PdfPreviewOptions, προκαλώντας το κλείσιμο του ρεύματος εξόδου."
type: docs
url: /el/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/) προκαλώντας το κλείσιμο της ροής εξόδου.

```python
def __init__(self, create_page_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Δημιουργεί μια ροή για μια συγκεκριμένη προεπισκόπηση σελίδας. |

## __init__ {#create_page_stream-release_page_stream}

Αρχικοποιεί ένα νέο στιγμιότυπο του PdfPreviewOptions που επιστρέφει τη ροή εξόδου στον πελάτη για περαιτέρω χρήση.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Δημιουργεί μια ροή για μια συγκεκριμένη προεπισκόπηση σελίδας. |
| release_page_stream | `ReleasePageStream` | Ειδοποιεί ότι η δημιουργία της προεπισκόπησης σελίδας ολοκληρώθηκε και λαμβάνει τη ροή εξόδου. |

### Δείτε επίσης
* class [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/)
