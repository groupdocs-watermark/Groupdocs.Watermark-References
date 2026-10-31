---
title: "encrypt μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Κρυπτογραφεί το έγγραφο χρησιμοποιώντας τον ίδιο κωδικό πρόσβασης ως κωδικό χρήστη και κωδικό ιδιοκτήτη."
type: docs
url: /el/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

Κρυπτογραφεί το έγγραφο χρησιμοποιώντας τον ίδιο κωδικό πρόσβασης ως κωδικό χρήστη και κωδικό ιδιοκτήτη.

```python
def encrypt(self, password):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| password | `str` | Κωδικός χρήστη και κωδικός ιδιοκτήτη. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

Κρυπτογραφεί το περιεχόμενο.

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| user_password | `str` | Κωδικός χρήστη. |
| owner_password | `str` | Κωδικός ιδιοκτήτη. |
| permissions | `PdfPermissions` | Δικαιώματα περιεχομένου. |
| crypto_algorithm | `PdfCryptoAlgorithm` | Κρυπτογραφικός αλγόριθμος. |

### Δείτε επίσης
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
