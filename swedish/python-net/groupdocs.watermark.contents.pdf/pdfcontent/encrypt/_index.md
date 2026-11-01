---
title: "encrypt-metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Krypterar dokumentet med samma lösenord som användarlösenordet och ägarlösenordet."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

Krypterar dokumentet med samma lösenord som användarlösenordet och ägarlösenordet.

```python
def encrypt(self, password):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| password | `str` | Användar- och ägarlösenord. |

### Exempel

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

Krypterar innehållet.

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| user_password | `str` | Användarlösenord. |
| owner_password | `str` | Ägarlösenord. |
| permissions | `PdfPermissions` | Innehållstillstånd. |
| crypto_algorithm | `PdfCryptoAlgorithm` | Kryptografisk algoritm. |

### Se även
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
