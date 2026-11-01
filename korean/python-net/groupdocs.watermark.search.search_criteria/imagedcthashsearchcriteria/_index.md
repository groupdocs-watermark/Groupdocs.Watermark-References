---
title: "ImageDctHashSearchCriteria 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "문서에서 이미지를 찾기 위한 검색 기준을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/
is_root: false
weight: 40
---


## ImageDctHashSearchCriteria class

문서에서 이미지를 찾기 위한 검색 기준을 나타냅니다.

이 검색 기준은 이미지 유사도 계산을 위해 DCT 기반 지각 이미지 해시를 사용합니다. 자세히 알아보기: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

ImageDctHashSearchCriteria 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#file_path) | 지정된 파일 경로로 새로운 ImageDctHashSearchCriteria 인스턴스를 초기화합니다. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#stream) | 제공된 이미지 스트림으로 새로운 ImageDctHashSearchCriteria 인스턴스를 초기화합니다. |

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
| [max_difference](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/max_difference/) | 이미지 간 허용되는 최대 차이입니다. ([`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/)에서 상속됨) |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | 특정 페이지 번호 목록입니다. ([`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)에서 상속됨) |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")
```

### Guides
`ImageDctHashSearchCriteria`를 사용하는 작업 가이드:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### 또 보기
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
