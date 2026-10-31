---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationWatermarkableImage χρησιμοποιώντας τα καθορισμένα δεδομένα εικόνας."
type: docs
url: /el/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) χρησιμοποιώντας τα καθορισμένα δεδομένα εικόνας.

```python
def __init__(self, image_data):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_data | `list[int]` | Ο πίνακας των μη υπογεγραμμένων byte από τα οποία θα δημιουργηθεί το `PresentationWatermarkableImage`. |

### Παράδειγμα

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### Δείτε επίσης
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
