---
title: "SpreadsheetWatermarkHeaderFooterOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "스프레드시트 머리글/바닥글에 워터마크를 추가할 때의 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/
is_root: false
weight: 100
---


## SpreadsheetWatermarkHeaderFooterOptions class

스프레드시트 머리글/바닥글에 워터마크를 추가할 때의 옵션을 나타냅니다.

자세히 알아보기:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

SpreadsheetWatermarkHeaderFooterOptions 타입은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/__init__/) | 새 인스턴스를 초기화합니다 [`SpreadsheetWatermarkHeaderFooterOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/) 클래스의. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/worksheet_index/) | 워터마크를 추가할 워크시트의 인덱스입니다. |

### 필드
| 필드 | 설명 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | 클래스의 기본값을 가져옵니다. ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)에서 상속됨) |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetWatermarkHeaderFooterOptions
from groupdocs.watermark.watermarks import Font, TextWatermark
load_options = SpreadsheetLoadOptions()
with Watermarker("./test.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 14))
    options = SpreadsheetWatermarkHeaderFooterOptions()
    options.worksheet_index = 0
    watermarker.add(watermark, options)
    watermarker.save()
```

### 또 보기
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
