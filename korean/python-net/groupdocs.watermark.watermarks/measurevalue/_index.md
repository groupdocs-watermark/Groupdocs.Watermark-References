---
title: "MeasureValue 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "특정 유형과 숫자 값을 가진 측정값을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

특정 유형과 숫자 값을 가진 측정값을 나타냅니다.

MeasureValue 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### 속성
| 속성 | 설명 |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | 측정 유형. |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | 측정값의 수치; 0보다 커야 합니다. |

### 예시

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# 페이지 비율로 표현된 측정값을 생성합니다
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
`MeasureValue`를 사용하는 작업 가이드:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### 또 보기
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
