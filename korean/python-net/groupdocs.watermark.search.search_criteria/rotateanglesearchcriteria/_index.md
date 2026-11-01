---
title: "RotateAngleSearchCriteria 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "워터마크 회전 각도로 필터링을 허용하는 기준을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/
is_root: false
weight: 120
---


## RotateAngleSearchCriteria class

워터마크 회전 각도로 필터링을 허용하는 기준을 나타냅니다.

자세히 알아보기:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

RotateAngleSearchCriteria 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/#min_angle-max_angle) | 시작 각도와 끝 각도를 사용하여 새로운 RotateAngleSearchCriteria를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | 논리 AND 연산자를 사용하여 이 SearchCriteria를 다른 기준과 결합합니다. ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) 로부터 상속됨) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) 로부터 상속됨) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | 이 SearchCriteria를 부정합니다. ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) 로부터 상속됨) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | 논리 OR 연산자를 사용하여 이 SearchCriteria를 다른 기준과 결합합니다. ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) 로부터 상속됨) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) 로부터 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [maximum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/maximum_angle/) | 끝 각도(도 단위)입니다. |
| [minimum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/minimum_angle/) | 시작 각도(도). |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

def search_by_angle():
    with Watermarker("./document.pdf") as watermarker:
        angle_criteria = RotateAngleSearchCriteria(30, 60)
        possible = watermarker.search(angle_criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_angle()
```

### Guides
`RotateAngleSearchCriteria`를 사용하는 작업 가이드:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### 또 보기
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
