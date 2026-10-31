---
title: "save μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αποθηκεύει τα δεδομένα του εγγράφου στη βασική ροή."
type: docs
url: /el/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

Αποθηκεύει τα δεδομένα του εγγράφου στη βασική ροή.

Μάθετε περισσότερα για την αποθήκευση των εγγράφων: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker(r"D:\\test.msg") as watermarker:
    criteria = TextSearchCriteria("test", False)
    watermarks = watermarker.search(criteria)
    watermarker.remove(watermarks)
    watermarker.save()
```

## save {#file_path}

Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου.

Μάθετε περισσότερα για την αποθήκευση των εγγράφων: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή αρχείου για την αποθήκευση των δεδομένων του εγγράφου. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

def add_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)
        watermarker.save("output.pdf")
```

## save {#document}

Αποθηκεύει το έγγραφο στην καθορισμένη ροή.

Μάθετε περισσότερα για την αποθήκευση των εγγράφων στο https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, document):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή για την αποθήκευση των δεδομένων του εγγράφου. |

### Παράδειγμα

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    stream = BytesIO()
    watermarker.save(stream)
    # `stream` τώρα περιέχει τα αποθηκευμένα bytes PDF
```

## save {#options}

Αποθηκεύει τα δεδομένα του εγγράφου στη βασική ροή χρησιμοποιώντας επιλογές αποθήκευσης.

Μάθετε περισσότερα για την αποθήκευση των εγγράφων.

```python
def save(self, options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | `SaveOptions` | Πρόσθετες επιλογές για χρήση κατά την αποθήκευση ενός εγγράφου. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save(SaveOptions())
```

## save {#file_path-options}

Αποθηκεύει το έγγραφο στην καθορισμένη θέση αρχείου χρησιμοποιώντας επιλογές αποθήκευσης.

Μάθετε περισσότερα για την αποθήκευση των εγγράφων: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή αρχείου για την αποθήκευση των δεδομένων του εγγράφου. |
| options | `SaveOptions` | Πρόσθετες επιλογές για χρήση κατά την αποθήκευση ενός εγγράφου. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font
from groupdocs.watermark.options import SaveOptions

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save("output.pdf", SaveOptions())
```

## save {#document-options}

Αποθηκεύει το έγγραφο στην καθορισμένη ροή χρησιμοποιώντας επιλογές αποθήκευσης.

Μάθετε περισσότερα για την αποθήκευση των εγγράφων στην τεκμηρίωση του GroupDocs.

```python
def save(self, document, options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document | `io.RawIOBase` | Η ροή για την αποθήκευση των δεδομένων του εγγράφου. |
| options | `SaveOptions` | Πρόσθετες επιλογές για χρήση κατά την αποθήκευση ενός εγγράφου. |

### Παράδειγμα

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

def add_watermark_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)

        stream = BytesIO()
        watermarker.save(stream, SaveOptions())
        # stream τώρα περιέχει τα αποθηκευμένα δεδομένα PDF
        # π.χ., γράψτε σε ένα αρχείο
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### Δείτε επίσης
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
