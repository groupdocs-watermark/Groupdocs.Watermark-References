---
title: "SpreadsheetLoadOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "스프레드시트 문서에 대한 문서 로드 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/
is_root: false
weight: 40
---


## SpreadsheetLoadOptions class

스프레드시트 문서에 대한 문서 로드 옵션을 나타냅니다.

SpreadsheetLoadOptions 타입은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/) | 새 인스턴스를 초기화합니다 [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) 클래스의. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/#password) | 지정된 비밀번호와 함께 [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) 클래스의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | 파일 유형으로, 형식(예: docx, pdf, xlsx 등)을 나타냅니다. ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)에서 상속됨) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | 문서의 형식 패밀리로, 유형(예: Image, Pdf, Spreadsheet 등)을 나타냅니다. ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)에서 상속됨) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | 암호화된 문서를 열기 위한 비밀번호입니다. ([`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)에서 상속됨) |

### 필드
| 필드 | 설명 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/default/) | 클래스의 기본값을 가져옵니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
    # 여기에서 워터마크 작업을 수행합니다
    pass
```

### 또 보기
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
