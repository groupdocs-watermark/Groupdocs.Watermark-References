---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "PagesSetup 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.watermarks/pagessetup/__init__/
is_root: false
weight: 10
---


## __init__

[`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/) 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#all_pages-first_page-last_page-odd_pages-even_pages-pages-page_number}

지정된 매개변수로 새 PagesSetup 인스턴스를 초기화합니다.

```python
def __init__(self, all_pages, first_page, last_page, odd_pages, even_pages, pages, page_number):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| all_pages | `bool` | 모든 페이지를 포함할지 여부. |
| first_page | `bool` | 첫 페이지를 포함할지 여부. |
| last_page | `bool` | 마지막 페이지를 포함할지 여부. |
| odd_pages | `bool` | 홀수 페이지를 포함할지 여부. |
| even_pages | `bool` | 짝수 페이지를 포함할지 여부. |
| pages | `List[int]` | 포함할 특정 페이지 번호 목록입니다. |
| page_number | `Optional[int]` | 현재 페이지의 인덱스. |

### 또 보기
* class [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/)
