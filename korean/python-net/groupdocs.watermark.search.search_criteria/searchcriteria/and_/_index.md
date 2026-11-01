---
title: "and_ 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "논리 AND 연산자를 사용하여 이 SearchCriteria를 다른 기준과 결합합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/
is_root: false
weight: 1010
---


## and_ {#other}

논리 AND 연산자를 사용하여 이 SearchCriteria를 다른 기준과 결합합니다.

```python
def and_(self, other):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | `SearchCriteria` | 결합할 검색 기준입니다. |

**Returns:** Combined search criteria.

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

with Watermarker("./document.pdf") as watermarker:
    image_criteria = ImageDctHashSearchCriteria("./logo.png")
    text_criteria = TextSearchCriteria("CONFIDENTIAL")
    angle_criteria = RotateAngleSearchCriteria(30, 60)

    # 기준 결합: (image OR text) AND angle
    combined = image_criteria.or_(text_criteria).and_(angle_criteria)
    results = watermarker.search(combined)
    print("Found", len(results), "possible watermark(s)")
```

### 또 보기
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
