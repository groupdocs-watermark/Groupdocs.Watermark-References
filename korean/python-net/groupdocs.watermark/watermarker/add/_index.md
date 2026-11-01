---
title: "add 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "로드된 문서에 워터마크를 추가합니다."
type: docs
url: /ko/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

로드된 문서에 워터마크를 추가합니다.

GroupDocs 문서에서 워터마크 추가에 대해 자세히 알아보세요.

```python
def add(self, watermark):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| watermark | `Watermark` | 문서에 추가할 워터마크입니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

## add {#watermark-options}

워터마크 옵션을 사용하여 로드된 문서에 워터마크를 추가합니다.

워터마크 추가에 대해 자세히 알아보려면: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| watermark | `Watermark` | 문서에 추가할 워터마크입니다. |
| options | `WatermarkOptions` | 워터마크를 추가할 때 사용할 추가 옵션입니다. |

**Returns:** None.

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### 또 보기
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
