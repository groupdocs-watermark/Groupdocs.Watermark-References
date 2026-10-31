---
title: "Κλάση EmailLoadOptions"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά τις επιλογές φόρτωσης εγγράφου για ένα μήνυμα email."
type: docs
url: /el/python-net/groupdocs.watermark.options.email/emailloadoptions/
is_root: false
weight: 10
---


## EmailLoadOptions class

Αναπαριστά τις επιλογές φόρτωσης εγγράφου για ένα μήνυμα email.

Ο τύπος EmailLoadOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/). |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Ο τύπος του αρχείου, που υποδεικνύει τη μορφή του (π.χ., docx, pdf, xlsx κ.λπ.). (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Η οικογένεια μορφής του εγγράφου, που υποδεικνύει τον τύπο του (π.χ., Image, Pdf, Spreadsheet κ.λπ.). (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Ο κωδικός πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου. (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # Διαχειριστείτε το περιεχόμενο του email εδώ
    watermarker.save("./output.msg")
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
