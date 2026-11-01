---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "PdfPreviewOptions 클래스를 새 인스턴스로 초기화하고 출력 스트림을 닫습니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

`[`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/)` 클래스의 새 인스턴스를 초기화하여 출력 스트림이 닫히도록 합니다.

```python
def __init__(self, create_page_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |

## __init__ {#create_page_stream-release_page_stream}

출력 스트림을 클라이언트에 반환하여 추가 사용이 가능하도록 하는 새 PdfPreviewOptions 인스턴스를 초기화합니다.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 특정 페이지 미리보기를 위한 스트림을 생성합니다. |
| release_page_stream | `ReleasePageStream` | 페이지 미리보기 생성이 완료되었음을 알리고 출력 스트림을 가져옵니다. |

### 또 보기
* class [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/)
