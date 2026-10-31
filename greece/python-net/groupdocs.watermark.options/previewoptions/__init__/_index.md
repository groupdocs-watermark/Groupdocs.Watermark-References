---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία PreviewOptions που κλείνει τη ροή εξόδου μετά τη χρήση."
type: docs
url: /el/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Αρχικοποιεί μια νέα παρουσία PreviewOptions που κλείνει τη ροή εξόδου μετά τη χρήση.

```python
def __init__(self, create_page_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – Δημιουργεί μια ροή για μια συγκεκριμένη προεπισκόπηση σελίδας. |

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

## __init__ {#create_page_stream-release_page_stream}

Αρχικοποιεί μια νέα παρουσία PreviewOptions που επιστρέφει τη ροή εξόδου στον πελάτη για περαιτέρω χρήση.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable που δημιουργεί μια ροή για μια συγκεκριμένη προεπισκόπηση σελίδας. Λαμβάνει τον αριθμό σελίδας (`int`) και πρέπει να επιστρέφει μια εγγράψιμη ροή (`io.RawIOBase`). |
| release_page_stream | `ReleasePageStream` | Callable που καλείται όταν η δημιουργία της προεπισκόπησης σελίδας ολοκληρωθεί και παρέχει τη ροή εξόδου. |

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

### Δείτε επίσης
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
