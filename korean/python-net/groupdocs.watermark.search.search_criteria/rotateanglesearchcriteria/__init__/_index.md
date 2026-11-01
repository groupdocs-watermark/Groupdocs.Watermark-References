---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "시작 각도와 끝 각도를 사용하여 새로운 RotateAngleSearchCriteria를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

시작 각도와 끝 각도를 사용하여 새로운 RotateAngleSearchCriteria를 초기화합니다.

```python
def __init__(self, min_angle, max_angle):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| min_angle | `float` | 시작 각도(도). |
| max_angle | `float` | 끝 각도(도 단위)입니다. |

### 예시

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# 30도에서 60도 사이로 회전된 워터마크를 검색합니다
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### 또 보기
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
