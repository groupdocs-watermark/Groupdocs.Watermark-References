---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지정된 파일 경로로 새로운 ImageDctHashSearchCriteria 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

지정된 파일 경로로 새로운 ImageDctHashSearchCriteria 인스턴스를 초기화합니다.

```python
def __init__(self, file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 이미지를 로드할 파일 경로입니다. |

### 예시

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

제공된 이미지 스트림으로 새로운 ImageDctHashSearchCriteria 인스턴스를 초기화합니다.

```python
def __init__(self, stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 이미지를 로드할 스트림입니다. |

### 또 보기
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
