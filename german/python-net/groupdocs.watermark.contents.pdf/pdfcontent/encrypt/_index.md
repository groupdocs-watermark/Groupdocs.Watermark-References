---
title: "encrypt-Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Verschlüsselt das Dokument mit demselben Passwort wie Benutzer- und Eigentümerpasswort."
type: docs
url: /de/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

Verschlüsselt das Dokument mit demselben Passwort wie Benutzer- und Eigentümerpasswort.

```python
def encrypt(self, password):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| password | `str` | Benutzer- und Eigentümerpasswort. |

### Beispiel

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

Verschlüsselt den Inhalt.

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| user_password | `str` | Benutzerpasswort. |
| owner_password | `str` | Eigentümerpasswort. |
| permissions | `PdfPermissions` | Inhaltsberechtigungen. |
| crypto_algorithm | `PdfCryptoAlgorithm` | Kryptografischer Algorithmus. |

### Siehe auch
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
