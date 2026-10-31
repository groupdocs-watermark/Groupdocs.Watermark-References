---
title: "μέθοδος from_extension"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιστοιχίζει την επέκταση αρχείου με τον τύπο αρχείου."
type: docs
url: /el/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Αντιστοιχίζει την επέκταση αρχείου με τον τύπο αρχείου.

```python
def from_extension(cls, extension):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| extension | `str` | Η επέκταση αρχείου (συμπεριλαμβανομένου του σημείου "."). |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| Εγείρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εκτοπίζεται όταν το `extension` είναι null ή κενή συμβολοσειρά. |

### Δείτε επίσης
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
