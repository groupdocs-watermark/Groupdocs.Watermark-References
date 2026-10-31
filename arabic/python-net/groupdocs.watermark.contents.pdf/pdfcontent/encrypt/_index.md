---
title: "طريقة encrypt"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يشفّر المستند باستخدام نفس كلمة المرور ككلمة مرور المستخدم وكلمة مرور المالك."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

يشفّر المستند باستخدام نفس كلمة المرور ككلمة مرور المستخدم وكلمة مرور المالك.

```python
def encrypt(self, password):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| password | `str` | كلمة مرور المستخدم والمالك. |

### مثال

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

يشفّر المحتوى.

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| user_password | `str` | كلمة مرور المستخدم. |
| owner_password | `str` | كلمة مرور المالك. |
| permissions | `PdfPermissions` | أذونات المحتوى. |
| crypto_algorithm | `PdfCryptoAlgorithm` | الخوارزمية التشفيرية. |

### انظر أيضًا
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
