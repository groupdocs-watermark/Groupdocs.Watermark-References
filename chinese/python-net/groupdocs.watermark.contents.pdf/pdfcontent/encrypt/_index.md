---
title: "encrypt 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用与用户密码和所有者密码相同的密码加密文档。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

使用与用户密码和所有者密码相同的密码加密文档。

```python
def encrypt(self, password):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| password | `str` | 用户和所有者密码。 |

### 示例

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

加密内容。

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| user_password | `str` | 用户密码。 |
| owner_password | `str` | 所有者密码。 |
| permissions | `PdfPermissions` | 内容权限。 |
| crypto_algorithm | `PdfCryptoAlgorithm` | 加密算法。 |

### 另请参见
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
