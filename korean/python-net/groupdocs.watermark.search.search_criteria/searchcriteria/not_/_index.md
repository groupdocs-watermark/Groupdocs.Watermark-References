---
title: "not_ 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "이 SearchCriteria를 부정합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/
is_root: false
weight: 1030
---


## not_

이 SearchCriteria를 부정합니다.

```python
def not_(self):
    ...
```

**Returns:** Combined search criteria.

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_not():
    with Watermarker("./document.pdf") as watermarker:
        text_criteria = TextSearchCriteria("CONFIDENTIAL")
        not_criteria = text_criteria.not_()
        results = watermarker.search(not_criteria)
        print("Found", len(results), "watermarks that do NOT match the text")
```

### 또 보기
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
