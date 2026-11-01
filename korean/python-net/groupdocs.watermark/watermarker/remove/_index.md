---
title: "remove 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "문서에서 워터마크를 제거합니다."
type: docs
url: /ko/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

문서에서 워터마크를 제거합니다.

워터마크 제거에 대해 자세히 알아보기: 찾은 워터마크 제거.

```python
def remove(self, possible_watermark):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | 제거할 워터마크. |

### 예시

```python
from groupdocs.watermark import Watermarker

def remove_first_watermark():
    with Watermarker("./document.pdf") as watermarker:
        watermarks = watermarker.search()
        if watermarks:
            watermarker.remove(watermarks[0])
        watermarker.save("./output.pdf")
```

## remove {#possible_watermarks}

문서에서 컬렉션에 있는 모든 워터마크를 제거합니다.

GroupDocs 문서에서 워터마크 제거에 대해 자세히 알아보기.

```python
def remove(self, possible_watermarks):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | 제거할 워터마크 컬렉션. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # 인덱스가 유효하도록 역순으로 제거하십시오.
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### 또 보기
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
