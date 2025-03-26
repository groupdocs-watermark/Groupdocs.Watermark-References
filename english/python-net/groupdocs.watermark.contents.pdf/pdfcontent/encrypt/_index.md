---
title: encrypt method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 30
---

## encrypt {#str}

Encrypts the document using the same password as user password and owner password.



```python
def encrypt(self, password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| password | str | User and owner password. |


## encrypt {#str-str-groupdocs.watermark.contents.pdf.PdfPermissions-groupdocs.watermark.contents.pdf.PdfCryptoAlgorithm}

Encrypts the content.



```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| user_password | str | User password. |
| owner_password | str | Owner password. |
| permissions | [`PdfPermissions`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpermissions) | Content permissions. |
| crypto_algorithm | [`PdfCryptoAlgorithm`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcryptoalgorithm) | Cryptographic algorithm. |



### See Also
* module [`groupdocs.watermark.contents.pdf`](../../)
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent)
