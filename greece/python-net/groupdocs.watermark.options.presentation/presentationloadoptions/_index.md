---
title: "PresentationLoadOptions κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά τις επιλογές φόρτωσης εγγράφου για ένα έγγραφο Presentation."
type: docs
url: /el/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/
is_root: false
weight: 30
---


## PresentationLoadOptions class

Αναπαριστά τις επιλογές φόρτωσης εγγράφου για ένα έγγραφο Presentation.

Ο τύπος PresentationLoadOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/#password) | Αρχικοποιεί μια νέα παρουσία της κλάσης PresentationLoadOptions με καθορισμένο κωδικό πρόσβασης. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Ο τύπος του αρχείου, που υποδεικνύει τη μορφή του (π.χ., docx, pdf, xlsx κ.λπ.). (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Η οικογένεια μορφής του εγγράφου, που υποδεικνύει τον τύπο του (π.χ., Image, Pdf, Spreadsheet κ.λπ.). (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Ο κωδικός πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου. (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
    # εργασία με το έγγραφο
    pass
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
