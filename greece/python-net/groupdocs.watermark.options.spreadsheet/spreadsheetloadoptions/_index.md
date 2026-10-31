---
title: "Κλάση SpreadsheetLoadOptions"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά επιλογές φόρτωσης εγγράφου για έγγραφο Spreadsheet."
type: docs
url: /el/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/
is_root: false
weight: 40
---


## SpreadsheetLoadOptions class

Αναπαριστά επιλογές φόρτωσης εγγράφου για έγγραφο Spreadsheet.

Ο τύπος SpreadsheetLoadOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/#password) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) με καθορισμένο κωδικό πρόσβασης. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Ο τύπος του αρχείου, που υποδεικνύει τη μορφή του (π.χ., docx, pdf, xlsx κ.λπ.). (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Η οικογένεια μορφής του εγγράφου, που υποδεικνύει τον τύπο του (π.χ., Image, Pdf, Spreadsheet κ.λπ.). (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Ο κωδικός πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου. (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
    # εκτελέστε λειτουργίες υδατογραφήματος εδώ
    pass
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
