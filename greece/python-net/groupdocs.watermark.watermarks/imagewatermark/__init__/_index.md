---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία του ImageWatermark με καθορισμένη διαδρομή αρχείου."
type: docs
url: /el/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Αρχικοποιεί μια νέα παρουσία του ImageWatermark με καθορισμένη διαδρομή αρχείου.

```python
def __init__(self, file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή προς την εικόνα που θα χρησιμοποιηθεί ως υδατογράφημα. |

### Παράδειγμα

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.watermarks import ImageWatermark

    with Watermarker("document.docx") as watermarker:
        watermark = ImageWatermark("logo.png")
        watermarker.add(watermark)
        watermarker.save("watermarked.docx")
    ```

## __init__ {#stream}

Αρχικοποιεί ένα νέο ImageWatermark με το παρεχόμενο ρεύμα εικόνας.

```python
def __init__(self, stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή που περιέχει την εικόνα που θα χρησιμοποιηθεί ως υδατογράφημα. |

### Παράδειγμα

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

with open("logo.png", "rb") as f:
    image_data = f.read()

with Watermarker("sample.docx") as watermarker:
    with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
        watermarker.add(watermark)
    watermarker.save("watermarked.docx")
```

### Δείτε επίσης
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
