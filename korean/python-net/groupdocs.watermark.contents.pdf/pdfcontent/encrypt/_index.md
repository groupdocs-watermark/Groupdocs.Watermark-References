---
title: "encrypt 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "사용자 비밀번호와 소유자 비밀번호와 동일한 비밀번호를 사용하여 문서를 암호화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
is_root: false
weight: 1020
---


## encrypt {#password}

사용자 비밀번호와 소유자 비밀번호와 동일한 비밀번호를 사용하여 문서를 암호화합니다.

```python
def encrypt(self, password):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| password | `str` | 사용자 및 소유자 비밀번호. |

### 예시

```python
from groupdocs.watermark import Watermarker

watermarker = Watermarker("sample.pdf")
pdf_content = watermarker.get_content()
pdf_content.encrypt("myPassword")
watermarker.save("encrypted.pdf")
```

## encrypt {#user_password-owner_password-permissions-crypto_algorithm}

콘텐츠를 암호화합니다.

```python
def encrypt(self, user_password, owner_password, permissions, crypto_algorithm):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| user_password | `str` | 사용자 비밀번호. |
| owner_password | `str` | 소유자 비밀번호. |
| permissions | `PdfPermissions` | 콘텐츠 권한. |
| crypto_algorithm | `PdfCryptoAlgorithm` | 암호화 알고리즘. |

### 또 보기
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
