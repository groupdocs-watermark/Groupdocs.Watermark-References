---
title: "Hello, World!"
linkTitle: "Hello, World!"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "간단한 예제를 만들고 실행하여 .NET을 통해 Python용 GroupDocs.Watermark를 빠르게 시작하십시오."
type: docs
url: /ko/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
\"Hello, World!\" 예제는 .NET을 통해 Python용 GroupDocs.Watermark를 탐색할 때 흔히 첫 번째 단계입니다. 이는 개발 환경이 올바르게 설정되었고 라이브러리가 예상대로 작동하는지 확인하는 간단한 테스트 역할을 합니다.

## Overview
.NET을 통해 Python용 GroupDocs.Watermark를 사용하면 다양한 문서 형식에서 워터마크를 추가, 검색 및 제거할 수 있습니다. 다양한 [supported formats](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) 덕분에 여러 사용 사례에 유연하게 적용됩니다.

## How to add a watermark
다음 단계에서는 .NET을 통해 Python용 GroupDocs.Watermark를 사용하여 문서에 텍스트 워터마크를 추가하는 방법을 보여줍니다.

1. 필요한 `groupdocs.watermark` 클래스를 가져옵니다.
2. 샘플 문서의 경로를 사용하여 [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)를 엽니다.
3. 원하는 텍스트와 글꼴을 사용하여 [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)를 생성하고 스타일을 지정합니다.
4. `add()`를 사용하여 워터마크를 적용합니다.
5. 결과를 저장합니다.

## Complete example
아래 예제는 반투명하고 대각선으로 배치된 \"Hello, Watermark!\" 텍스트 워터마크를 추가하고 결과를 저장합니다:

{{< tabs \"code-example-hello-world\" >}}
{{< tab \"hello_world.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # 문서를 열고 단일 텍스트 워터마크를 추가한 뒤 결과를 저장합니다
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("Hello, Watermark!", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermark.rotate_angle = 45.0
        watermarker.add(watermark)
        watermarker.save("./output.pdf")

    print("Watermark added successfully. Output saved to ./output.pdf.")

if __name__ == "__main__":
    hello_world()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

워터마크는 `output.pdf`와 동일한 PDF 형식으로 다시 저장됩니다. 다른 문서에 스탬프를 찍으려면 입력 경로와 출력 확장자를 변경하십시오 — GroupDocs.Watermark는 입력 문서의 형식으로 저장합니다.

## Additional resources
이 데모는 GroupDocs.Watermark for Python via .NET [코드 샘플](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/)을(를) 참조합니다.
