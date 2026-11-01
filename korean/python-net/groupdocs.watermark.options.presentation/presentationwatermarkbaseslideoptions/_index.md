---
title: "PresentationWatermarkBaseSlideOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "프레젠테이션 문서에 워터마크 추가 옵션을 위한 기본 클래스."
type: docs
url: /ko/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
is_root: false
weight: 70
---


## PresentationWatermarkBaseSlideOptions class

프레젠테이션 문서에 워터마크 추가 옵션을 위한 기본 클래스.

자세히 알아보기:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

PresentationWatermarkBaseSlideOptions 형식은 다음 멤버를 노출합니다:

### 속성
| 속성 | 설명 |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | 도형에 연결될 설명(대체) 텍스트입니다. |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | 워터마크에 적용할 효과이며, [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) 또는 [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/) 인스턴스로 지정합니다. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | 이 속성은 PowerPoint에서 도형 편집이 금지되는지 여부를 나타냅니다. |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | 도형의 이름입니다. |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | 텍스트 워터마크 문자에 읽을 수 없는 문자가 혼합되어 있는지 여부를 나타내는 속성입니다. |

### 필드
| 필드 | 설명 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | 클래스의 기본값을 가져옵니다. ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)에서 상속됨) |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationWatermarkMasterSlideOptions
from groupdocs.watermark.options.presentation import PresentationWatermarkLayoutSlideOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./presentation.pptx") as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 8.0))

    master_options = PresentationWatermarkMasterSlideOptions()
    master_options.master_slide_index = 0
    watermarker.add(watermark, master_options)

    layout_options = PresentationWatermarkLayoutSlideOptions()
    layout_options.layout_slide_index = 0
    watermarker.add(watermark, layout_options)

    watermarker.save("./output.pptx")
```

### 또 보기
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
