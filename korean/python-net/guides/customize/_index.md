---
title: "워터마크 사용자 지정"
linkTitle: "Customize watermarks"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "GroupDocs.Watermark for Python via .NET를 사용하여 텍스트 또는 이미지 워터마크의 외관 및 위치를 조정합니다 — 색상, 글꼴, 회전, 불투명도, 크기 및 정렬 등."
type: docs
url: /ko/python-net/guides/customize/
is_root: false
weight: 60
---


GroupDocs.Watermark를 사용하면 워터마크의 모양과 표시 위치를 제어할 수 있습니다. 색상, 글꼴, 정렬, 회전, 불투명도 및 스케일을 조정하여 문서 스타일에 맞추세요.

## Customize text watermarks

다음과 같은 [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) 속성을 사용합니다: `foreground_color`, `opacity`, `rotate_angle`, `sizing_type`, `scale_factor`, `horizontal_alignment`, `vertical_alignment`, `x`, `y`, `width`, `height`, `consider_parent_margins`. 아래 예제는 "DRAFT" 워터마크를 페이지에 맞게 스케일링하고 45° 회전시켜 반투명하게 만듭니다.

{{< tabs "code-example-customize">}}
{{< tab "customize_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def customize_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("DRAFT", Font("Arial", 42.0))
        watermark.foreground_color = Color.dark_orange
        # 워터마크를 페이지에 상대적으로 스케일링하고 회전합니다.
        watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS
        watermark.scale_factor = 0.7
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.5
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    customize_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Apply branded or legal disclaimers in a consistent style across pages (for example, "Confidential – Do Not Distribute").

## Customize image watermarks

이미지 워터마크는 동일한 위치 지정, 회전 및 불투명도 속성을 지원합니다. 로고, 스탬프 또는 씰을 필요한 정확한 위치에 배치하세요:

{{< tabs "code-example-customize-image">}}
{{< tab "customize_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def customize_image_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        with ImageWatermark("./stamp.png") as watermark:
            watermark.horizontal_alignment = HorizontalAlignment.RIGHT
            watermark.vertical_alignment = VerticalAlignment.TOP
            watermark.rotate_angle = 15.0
            watermark.opacity = 0.8
            watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    customize_image_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`와 `stamp.png`는 이 예제에 사용된 샘플 파일입니다. [sample.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) 및 [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/stamp.png)를 다운로드하십시오.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 268 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_image_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}
