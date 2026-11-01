---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "출력 스트림이 닫히도록 PresentationPreviewOptions 클래스를 새 인스턴스로 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

출력 스트림이 닫히도록 PresentationPreviewOptions 클래스를 새 인스턴스로 초기화합니다.

```python
def __init__(self, create_page_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |

## __init__ {#create_page_stream-release_page_stream}

출력 스트림이 클라이언트에 반환되어 추가로 사용할 수 있도록 [`PresentationPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/)의 새 인스턴스를 초기화합니다.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |
| release_page_stream | `ReleasePageStream` | 페이지 미리보기 생성이 완료되었음을 알리고 출력 스트림을 가져옵니다. |

### 또 보기
* class [`PresentationPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/)
