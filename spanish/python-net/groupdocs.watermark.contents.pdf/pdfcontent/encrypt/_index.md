---
title: "método encrypt"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Encripta el documento usando la misma contraseña que la contraseña de usuario y la contraseña del propietario."
type: docs
url: /es/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

Encripta el documento usando la misma contraseña que la contraseña de usuario y la contraseña del propietario.

```python
def encrypt(self, password):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | `str` | Contraseña de usuario y propietario. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

Encripta el contenido.

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| user_password | `str` | Contraseña de usuario. |
| owner_password | `str` | Contraseña de propietario. |
| permissions | `PdfPermissions` | Permisos de contenido. |
| crypto_algorithm | `PdfCryptoAlgorithm` | Algoritmo criptográfico. |

### Ver también
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
