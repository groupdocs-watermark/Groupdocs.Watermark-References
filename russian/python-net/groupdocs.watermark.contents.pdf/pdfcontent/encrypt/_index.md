---
title: "Метод encrypt"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Шифрует документ, используя тот же пароль, что и пароль пользователя и пароль владельца."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

Шифрует документ, используя тот же пароль, что и пароль пользователя и пароль владельца.

```python
def encrypt(self, password):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| password | `str` | Пароль пользователя и владельца. |

### Пример

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

Шифрует содержимое.

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| user_password | `str` | Пароль пользователя. |
| owner_password | `str` | Пароль владельца. |
| permissions | `PdfPermissions` | Разрешения содержимого. |
| crypto_algorithm | `PdfCryptoAlgorithm` | Криптографический алгоритм. |

### См. также
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
