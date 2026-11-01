---
title: "encrypt メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "ユーザーパスワードとオーナーパスワードと同じパスワードを使用してドキュメントを暗号化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

ユーザーパスワードとオーナーパスワードと同じパスワードを使用してドキュメントを暗号化します。

```python
def encrypt(self, password):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| password | `str` | ユーザーと所有者のパスワード。 |

### 例

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

コンテンツを暗号化します。

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| user_password | `str` | ユーザーパスワード。 |
| owner_password | `str` | 所有者パスワード。 |
| permissions | `PdfPermissions` | コンテンツの権限。 |
| crypto_algorithm | `PdfCryptoAlgorithm` | 暗号アルゴリズム。 |

### 関連項目
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
