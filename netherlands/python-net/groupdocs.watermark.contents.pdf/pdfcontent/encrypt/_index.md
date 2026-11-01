---
title: "encrypt methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Versleutelt het document met hetzelfde wachtwoord als gebruikerswachtwoord en eigenaarwachtwoord."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

Versleutelt het document met hetzelfde wachtwoord als gebruikerswachtwoord en eigenaarwachtwoord.

```python
def encrypt(self, password):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| password | `str` | Gebruiker- en eigenarenwachtwoord. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

Versleutelt de inhoud.

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| user_password | `str` | Gebruikerswachtwoord. |
| owner_password | `str` | Eigenarenwachtwoord. |
| permissions | `PdfPermissions` | Inhoudsrechten. |
| crypto_algorithm | `PdfCryptoAlgorithm` | Cryptografisch algoritme. |

### Zie ook
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
