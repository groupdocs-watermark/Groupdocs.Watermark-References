---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "사용 후 출력 스트림을 닫는 새로운 PreviewOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

사용 후 출력 스트림을 닫는 새로운 PreviewOptions 인스턴스를 초기화합니다.

```python
def __init__(self, create_page_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – 특정 페이지 미리보기를 위한 스트림을 생성합니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # 렌더링할 각 페이지에 대한 쓰기 가능한 파일 스트림을 제공하십시오
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

## __init__ {#create_page_stream-release_page_stream}

추가 사용을 위해 출력 스트림을 클라이언트에 반환하는 새로운 PreviewOptions 인스턴스를 초기화합니다.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 특정 페이지 미리보기를 위한 스트림을 생성하는 Callable입니다. 페이지 번호(`int`)를 받아서 쓰기 가능한 스트림(`io.RawIOBase`)을 반환해야 합니다. |
| release_page_stream | `ReleasePageStream` | 페이지 미리보기 생성이 완료되면 호출되는 Callable이며, 출력 스트림을 제공합니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # 렌더링할 각 페이지에 대한 쓰기 가능한 파일 스트림을 제공하십시오
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### 또 보기
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
