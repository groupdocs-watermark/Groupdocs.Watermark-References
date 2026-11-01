---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지정된 정규식으로 새로운 TextSearchCriteria를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

지정된 정규식으로 새로운 TextSearchCriteria를 초기화합니다.

```python
def __init__(self, pattern):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | 일치시킬 정규식. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

검색 문자열과 대소문자 구분 비교 플래그를 사용하여 [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, search_string, is_match_case):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| search_string | `str` | 검색할 정확한 문자열. |
| is_match_case | `bool` | 비교 시 대소문자를 무시하려면 False, 그렇지 않으면 True. |

### 예시

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

검색 문자열을 사용하여 [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, search_string):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| search_string | `str` | 검색할 정확한 문자열. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

### 또 보기
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
