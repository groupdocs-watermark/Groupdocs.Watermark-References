---
title: "문서 미리보기"
linkTitle: "Document preview"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "GroupDocs.Watermark for Python via .NET를 사용하여 문서 페이지에 대한 미리보기 이미지(PNG/JPG/BMP)를 생성합니다."
type: docs
url: /ko/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark는 문서 페이지를 이미지로 렌더링할 수 있어 뷰어에서 문서를 완전히 열지 않고도 페이지 썸네일을 표시할 수 있습니다. 각 페이지에 대한 쓰기 가능한 파일 스트림을 제공하는 `create_page_stream` 콜백으로 렌더링을 제어합니다 — 라이브러리가 페이지 이미지를 해당 스트림에 쓰고 자동으로 닫아줍니다.

## Generate a document preview

`create_page_stream` 콜백과 함께 [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)를 설정하고, `preview_format`을 선택한 뒤 렌더링할 `page_numbers`를 지정합니다.

{{< tabs "code-example-preview">}}
{{< tab "generate_preview.py" >}}
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
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에 사용된 두 페이지 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf)를 클릭하세요.

{{< /tab >}}
{{< tab "generate-preview-outputs.zip" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

페이지 이미지는 현재 디렉터리에 기록됩니다 — 요청된 각 페이지당 하나의 PNG가 생성됩니다. 다른 형식의 경우 `PreviewFormats.JPEG` 또는 `PreviewFormats.BMP`를 사용하고, 렌더링 크기를 제어하려면 `options.width` / `options.height`를 설정합니다.

라이브러리는 페이지가 기록된 후 `create_page_stream`이 반환한 각 파일을 닫습니다. 페이지가 준비되는 즉시 작업을 수행하려면 두 번째 콜백을 전달합니다: `PreviewOptions(create_page_stream, release_page_stream)`는 해당 페이지에 대한 전체 이미지가 들어간 후 `create_page_stream`이 반환한 객체와 함께 `release_page_stream(page_number, stream)`를 호출합니다. 인수가 하나인 `release_page_stream(page_number)`도 사용할 수 있습니다. `create_page_stream`은 `io.BytesIO`를 반환할 수도 있는데, 이 경우 스트림은 열려 있으며 `release_page_stream`이 호출될 때까지 페이지 이미지를 보유합니다.

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
