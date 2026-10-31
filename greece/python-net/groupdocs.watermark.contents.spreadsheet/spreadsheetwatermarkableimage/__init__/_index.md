---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης SpreadsheetWatermarkableImage χρησιμοποιώντας τα καθορισμένα δεδομένα εικόνας."
type: docs
url: /el/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) χρησιμοποιώντας τα καθορισμένα δεδομένα εικόνας.

```python
def __init__(self, image_data):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_data | `list[int]` | Ο πίνακας των μη υπογεγραμμένων byte από τα οποία δημιουργείται το `SpreadsheetWatermarkableImage`. |

### Παράδειγμα

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### Δείτε επίσης
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
