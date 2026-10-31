---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης DiagramWatermarkableImage χρησιμοποιώντας τα καθορισμένα δεδομένα εικόνας."
type: docs
url: /el/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) χρησιμοποιώντας τα καθορισμένα δεδομένα εικόνας.

```python
def __init__(self, image_data):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_data | `list[int]` | Ο πίνακας των μη υπογεγραμμένων bytes από τον οποίο δημιουργείται το `DiagramWatermarkableImage`. |

### Παράδειγμα

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

with open("test.png", "rb") as f:
    img = gwc_vsdx.DiagramWatermarkableImage(f.read())
```

### Δείτε επίσης
* class [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/)
