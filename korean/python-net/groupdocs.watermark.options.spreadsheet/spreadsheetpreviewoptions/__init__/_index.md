---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "SpreadsheetPreviewOptions 클래스의 새 인스턴스를 초기화하며, 출력 스트림을 닫습니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

SpreadsheetPreviewOptions 클래스의 새 인스턴스를 초기화하며, 출력 스트림을 닫습니다.

```python
def __init__(self, create_page_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |

## __init__ {#create_page_stream-release_page_stream}

SpreadsheetPreviewOptions 클래스의 새 인스턴스를 초기화하여 출력 스트림을 클라이언트에 반환하고 이후에 사용할 수 있게 합니다.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |
| release_page_stream | `ReleasePageStream` | 페이지 미리보기 생성이 완료되었음을 알리고 출력 스트림을 가져옵니다. |

### 또 보기
* class [`SpreadsheetPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/)
