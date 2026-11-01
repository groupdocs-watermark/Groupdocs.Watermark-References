---
title: "encrypt yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belgeyi, kullanıcı şifresi ve sahip şifresiyle aynı şifreyi kullanarak şifreler."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

Belgeyi, kullanıcı şifresi ve sahip şifresiyle aynı şifreyi kullanarak şifreler.

```python
def encrypt(self, password):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| password | `str` | Kullanıcı ve sahibi şifresi. |

### Örnek

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

İçeriği şifreler.

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| user_password | `str` | Kullanıcı şifresi. |
| owner_password | `str` | Sahibi şifresi. |
| permissions | `PdfPermissions` | İçerik izinleri. |
| crypto_algorithm | `PdfCryptoAlgorithm` | Kriptografik algoritma. |

### Ayrıca Bakınız
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
