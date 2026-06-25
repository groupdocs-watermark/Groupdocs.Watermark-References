---
title: encrypt method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

Encrypts the document using the same password for both user and owner.

```python
def encrypt(self, password):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| password | `str` | User and owner password. |

**Returns:** None.

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

Encrypts the content.

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| user_password | `str` | User password. |
| owner_password | `str` | Owner password. |
| permissions | `PdfPermissions` | Content permissions. |
| crypto_algorithm | `PdfCryptoAlgorithm` | Cryptographic algorithm. |

### See Also
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
