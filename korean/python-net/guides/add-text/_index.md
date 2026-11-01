---
title: "텍스트 워터마크 추가"
linkTitle: "Add text watermarks"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "이 문서는 문서에 텍스트 워터마크를 추가하고 결과를 GroupDocs.Watermark for Python via .NET를 사용하여 저장하는 방법을 보여줍니다."
type: docs
url: /ko/python-net/guides/add-text/
is_root: false
weight: 40
---


GroupDocs.Watermark의 주요 기능 중 하나는 문서에 텍스트 워터마크를 추가하는 것입니다. 로컬 경로나 스트림에서 문서 또는 이미지에 워터마크를 추가할 수 있습니다. 지원되는 형식 전체 목록은 [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/) 를 확인하십시오.

## Add a text watermark

텍스트 워터마크를 추가하려면 다음 단계를 따르세요:

1. 문서를 열 때 경로(또는 스트림)를 [Watermarker](https://reference.groupdocs.com/watermark/python-net/) 클래스에 전달하고, `with` 블록을 사용하여 문서가 자동으로 해제되도록 합니다.
2. 원하는 텍스트와 [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)를 사용하여 [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)를 생성합니다.
3. 워터마크의 스타일을 지정합니다 — 예를 들어 `foreground_color`와 정렬을 설정합니다.
4. 워터마크를 적용하려면 `add()`를 호출하고 결과를 저장하려면 `save()`를 호출합니다.

{{< tabs \"code-example-add-text\">}}
{{< tab \"add_text_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # 텍스트 워터마크를 만들고 스타일을 지정합니다
        watermark = TextWatermark("Top Secret", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.4

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

프로그램을 실행합니다. 지정된 경로에 새 워터마크가 적용된 문서가 생성됩니다.

## What's next

GroupDocs.Watermark는 텍스트 워터마크를 위한 배경 및 전경 색상, 사용자 정의 글꼴, 불투명도, 회전, 타일링, 절대 또는 상대 위치 지정 등 다양한 기능을 제공합니다. 자세한 내용은 고급 가이드의 [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/)를 참조하십시오.
