---
title: "반복 워터마크 추가"
linkTitle: "Repeated watermarks"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "GroupDocs.Watermark for Python via .NET를 사용하여 간격, 회전 및 패턴과 함께 반복(타일) 텍스트 또는 이미지 워터마크를 추가합니다."
type: docs
url: /ko/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


반복(타일) 워터마크를 사용하면 텍스트 또는 이미지 패턴으로 전체 페이지를 덮을 수 있습니다. `tile_options`를 워터마크에 설정하여 간격, 회전, 오프셋을 제어하고 다양한 타일 템플릿을 선택할 수 있습니다.

## Add a repeated text watermark

아래 예제는 대각선 텍스트 워터마크를 전체 페이지에 타일링합니다. `line_spacing`와 `watermark_spacing`은 페이지의 백분율로 표시되며, `tile_type`은 타일 템플릿을 선택합니다.

{{< tabs "code-example-adding-repeated-watermarks">}}
{{< tab "add_repeated_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import (
    TextWatermark, Font, Color, TextAlignment,
    TileOptions, TileType, MeasureValue, TileMeasureType,
)

def add_repeated_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.gray
        watermark.opacity = 0.3
        watermark.rotate_angle = -45.0
        watermark.text_alignment = TextAlignment.CENTER

        # 줄 사이와 반복 워터마크 사이의 간격, 페이지의 백분율로
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # 워터마크를 전체 페이지에 타일링합니다
        tile_options = TileOptions()
        tile_options.tile_type = TileType.ONE_THIRD_OFFSET
        tile_options.line_spacing = line_spacing
        tile_options.watermark_spacing = watermark_spacing
        watermark.tile_options = tile_options

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_repeated_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

같은 방식으로 로고나 인장을 페이지 전체에 타일링하려면 [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)를 [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)로 교체할 수 있습니다 — 이미지 워터마크에 동일한 `tile_options`를 설정하십시오.

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
