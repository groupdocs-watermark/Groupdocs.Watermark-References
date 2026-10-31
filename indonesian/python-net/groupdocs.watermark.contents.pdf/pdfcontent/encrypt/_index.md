---
title: "metode encrypt"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mengenkripsi dokumen menggunakan kata sandi yang sama dengan kata sandi pengguna dan kata sandi pemilik."
type: docs
url: /id/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

Mengenkripsi dokumen menggunakan kata sandi yang sama dengan kata sandi pengguna dan kata sandi pemilik.

```python
def encrypt(self, password):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| password | `str` | Kata sandi pengguna dan pemilik. |

### Contoh

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

Mengenkripsi konten.

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| user_password | `str` | Kata sandi pengguna. |
| owner_password | `str` | Kata sandi pemilik. |
| permissions | `PdfPermissions` | Izin konten. |
| crypto_algorithm | `PdfCryptoAlgorithm` | Algoritma kriptografi. |

### Lihat Juga
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
