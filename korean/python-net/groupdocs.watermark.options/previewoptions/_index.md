---
title: "PreviewOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "미리보기 생성을 위한 요구 사항 및 스트림 대리자를 설정하는 옵션을 제공합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

미리보기 생성을 위한 요구 사항 및 스트림 대리자를 설정하는 옵션을 제공합니다.

PreviewOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | 사용 후 출력 스트림을 닫는 새로운 PreviewOptions 인스턴스를 초기화합니다. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | 추가 사용을 위해 출력 스트림을 클라이언트에 반환하는 새로운 PreviewOptions 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | 각 렌더링된 페이지에 대한 쓰기 가능한 스트림을 얻기 위해 사용되는 페이지 스트림 생성 대리자입니다. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | 페이지 미리보기 높이입니다. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | 미리보기를 생성할 페이지 번호 배열입니다. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | 미리보기 이미지 형식입니다. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | 페이지 미리보기 완료 대리자입니다. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | 페이지 미리보기 너비입니다. |

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

### Guides
`PreviewOptions`를 사용하는 작업 가이드:

* [Document preview](/watermark/python-net/guides/preview/)

### 또 보기
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
