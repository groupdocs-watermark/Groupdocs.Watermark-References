---
title: "metodo encrypt"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Cifra il documento usando la stessa password dell'utente e del proprietario."
type: docs
url: /it/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

Cifra il documento usando la stessa password dell'utente e del proprietario.

```python
def encrypt(self, password):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| password | `str` | Password utente e proprietario. |

### Esempio

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

Cifra il contenuto.

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| user_password | `str` | Password utente. |
| owner_password | `str` | Password proprietario. |
| permissions | `PdfPermissions` | Permessi del contenuto. |
| crypto_algorithm | `PdfCryptoAlgorithm` | Algoritmo crittografico. |

### Vedi anche
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
