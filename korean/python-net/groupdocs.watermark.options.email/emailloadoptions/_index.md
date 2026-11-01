---
title: "EmailLoadOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "이메일 메시지에 대한 문서 로드 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options.email/emailloadoptions/
is_root: false
weight: 10
---


## EmailLoadOptions class

이메일 메시지에 대한 문서 로드 옵션을 나타냅니다.

EmailLoadOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/) | [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/) 클래스의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | 파일 유형으로, 형식(예: docx, pdf, xlsx 등)을 나타냅니다. ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)에서 상속됨) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | 문서의 형식 패밀리로, 유형(예: Image, Pdf, Spreadsheet 등)을 나타냅니다. ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)에서 상속됨) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | 암호화된 문서를 열기 위한 비밀번호입니다. ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)에서 상속됨) |

### 필드
| 필드 | 설명 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/default/) | 클래스의 기본 값을 가져옵니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # 여기서 이메일 내용을 조작합니다
    watermarker.save("./output.msg")
```

### 또 보기
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
