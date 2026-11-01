---
title: "MultiframeImageWatermarkOptions 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "멀티프레임 이미지에 워터마크를 추가할 때의 워터마크 추가 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
is_root: false
weight: 70
---


## MultiframeImageWatermarkOptions class

멀티프레임 이미지에 워터마크를 추가할 때의 워터마크 추가 옵션을 나타냅니다.

자세히 보기: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

MultiframeImageWatermarkOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/) | 새 인스턴스를 초기화합니다 [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/) 클래스. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/#frame_index) | 프레임의 지정된 인덱스로 [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/) 클래스의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | 워터마크를 추가할 프레임의 인덱스입니다. |

### 필드
| 필드 | 설명 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | 클래스의 기본값을 가져옵니다. ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)에서 상속됨) |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.image import ImageLoadOptions, MultiframeImageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = ImageLoadOptions()
with Watermarker(r"C:\test.gif", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 12))
    options = MultiframeImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)
    watermarker.save()
```

### 또 보기
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
