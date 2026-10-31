---
title: "méthode encrypt"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Crypte le document en utilisant le même mot de passe que le mot de passe utilisateur et le mot de passe propriétaire."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

Crypte le document en utilisant le même mot de passe que le mot de passe utilisateur et le mot de passe propriétaire.

```python
def encrypt(self, password):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| password | `str` | Mot de passe utilisateur et propriétaire. |

### Exemple

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

Crypte le contenu.

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| user_password | `str` | Mot de passe utilisateur. |
| owner_password | `str` | Mot de passe propriétaire. |
| permissions | `PdfPermissions` | Permissions de contenu. |
| crypto_algorithm | `PdfCryptoAlgorithm` | Algorithme cryptographique. |

### Voir aussi
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
