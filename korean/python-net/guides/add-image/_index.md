---
title: "이미지 워터마크 추가"
linkTitle: "Add image watermarks"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "이 문서는 .NET을 통해 Python용 GroupDocs.Watermark로 문서에 이미지 워터마크를 추가하고 결과를 저장하는 방법을 보여줍니다."
type: docs
url: /ko/python-net/guides/add-image/
is_root: false
weight: 50
---


GroupDocs.Watermark의 주요 기능 중 하나는 문서에 이미지 워터마크를 추가하는 것입니다. 로컬 경로나 스트림에서 문서 또는 이미지에 워터마크를 추가할 수 있습니다. 지원되는 형식 전체 목록은 [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/)를 확인하십시오.

## Add an image watermark

이미지 워터마크를 추가하려면 다음 단계를 따르세요:

1. 문서의 경로(또는 스트림)를 [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) 클래스에 전달하여 문서를 엽니다.
2. 워터마크 이미지 파일(또는 스트림)에서 [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)를 생성합니다.
3. 워터마크 위치 지정 — 예를 들어, `horizontal_alignment`, `vertical_alignment`, 및 `opacity`를 설정합니다.
4. 워터마크를 적용하려면 `add()`를 호출하고 결과를 저장하려면 `save()`를 호출합니다.

{{< tabs "code-example-add-image">}}
{{< tab "add_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # 로고 파일을 사용하여 이미지 워터마크를 만들고 중앙에 배치합니다.
        watermark = ImageWatermark("./logo.png")
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.opacity = 0.7

        watermarker.add(watermark)
        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_image_watermark()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx`와 `logo.png`는 이 예제에 사용된 샘플 파일입니다. [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) 및 [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png)를 다운로드하십시오.

{{< /tab >}}
{{< tab \"output.docx\" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

GroupDocs.Watermark는 이미지 워터마크에 대한 더 많은 기능을 제공합니다 — 스트림에서 로드, 스케일링, 타일링, 절대 또는 상대 위치 지정 등. 고급 가이드에서 [Adding image watermarks](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/)를 확인하십시오.
