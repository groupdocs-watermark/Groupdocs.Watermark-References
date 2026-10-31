---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο αντικείμενο της κλάσης WordProcessingWatermarkableImage χρησιμοποιώντας τα καθορισμένα δεδομένα εικόνας."
type: docs
url: /el/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) χρησιμοποιώντας τα καθορισμένα δεδομένα εικόνας.

```python
def __init__(self, image_data):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_data | `list[int]` | Ο πίνακας των απρόσημων bytes από τα οποία δημιουργείται το `WordProcessingWatermarkableImage`. |

### Παράδειγμα

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### Δείτε επίσης
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
