---
title: "Κλάση PreviewOptions"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Παρέχει επιλογές για τον καθορισμό απαιτήσεων και αντιπροσώπων ροής για τη δημιουργία προεπισκόπησης."
type: docs
url: /el/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

Παρέχει επιλογές για τον καθορισμό απαιτήσεων και αντιπροσώπων ροής για τη δημιουργία προεπισκόπησης.

Ο τύπος PreviewOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | Αρχικοποιεί μια νέα παρουσία PreviewOptions που κλείνει τη ροή εξόδου μετά τη χρήση. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | Αρχικοποιεί μια νέα παρουσία PreviewOptions που επιστρέφει τη ροή εξόδου στον πελάτη για περαιτέρω χρήση. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | Ο delegate δημιουργίας ροής σελίδας που χρησιμοποιείται για την απόκτηση μιας εγγράψιμης ροής για κάθε αποδομένη σελίδα. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | Το ύψος προεπισκόπησης σελίδας. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | Ο πίνακας αριθμών σελίδων για τη δημιουργία προεπισκοπήσεων. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | Η μορφή εικόνας προεπισκόπησης. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | Ο delegate ολοκλήρωσης προεπισκόπησης σελίδας. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | Το πλάτος προεπισκόπησης σελίδας. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Παρέχετε ένα εγγράψιμο ρεύμα αρχείου για κάθε σελίδα προς απόδοση.
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `PreviewOptions`:

* [Document preview](/watermark/python-net/guides/preview/)

### Δείτε επίσης
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
