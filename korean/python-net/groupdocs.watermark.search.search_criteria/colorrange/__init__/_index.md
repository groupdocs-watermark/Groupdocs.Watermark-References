---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "ColorRange 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

새로운 [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) 클래스 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# 기본 색상 범위를 생성합니다
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

지정된 정확한 색상으로 새로운 [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) 인스턴스를 초기화합니다.

```python
def __init__(self, exact_color):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| exact_color | `Color` | 범위가 생성되는 정확한 색상입니다. |

### 또 보기
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
