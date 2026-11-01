---
title: "ColorRange 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "RGB 색상의 HSB 표현을 사용한 색상 범위를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

RGB 색상의 HSB 표현을 사용한 색상 범위를 나타냅니다.

ColorRange 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | 새로운 [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) 클래스 인스턴스를 초기화합니다. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | 지정된 정확한 색상으로 새로운 [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | 빈 색상만 범위에 포함되는지 여부를 나타내는 플래그입니다. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | 끝 밝기 값으로, 0.0(검정)에서 1.0(흰색)까지 범위입니다. |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | 끝 색조 값(도 단위)입니다. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | 끝 채도 값입니다. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | 시작 밝기 값으로, 0.0(검정)에서 1.0(흰색)까지 범위입니다. |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | 시작 색조 값(도 단위)입니다. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | 시작 채도 값입니다. |

### 예시

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# 전경 색상 매칭을 위한 색상 범위를 생성합니다
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
`ColorRange`를 사용하는 작업 가이드:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### 또 보기
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
