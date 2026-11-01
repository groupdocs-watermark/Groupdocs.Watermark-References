---
title: "or_ 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "논리 OR 연산자를 사용하여 이 SearchCriteria를 다른 기준과 결합합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

논리 OR 연산자를 사용하여 이 SearchCriteria를 다른 기준과 결합합니다.

```python
def or_(self, other):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | `SearchCriteria` | 결합할 검색 기준입니다. |

**Returns:** SearchCriteria: Combined search criteria.

### 예시

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import (
        ImageDctHashSearchCriteria,
        TextSearchCriteria,
    )

    with Watermarker("./document.pdf") as watermarker:
        image_criteria = ImageDctHashSearchCriteria("./logo.png")
        text_criteria = TextSearchCriteria("CONFIDENTIAL")
        combined = image_criteria.or_(text_criteria)
        results = watermarker.search(combined)
        print(f"Found {len(results)} possible watermark(s)")
    ```

### 또 보기
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
