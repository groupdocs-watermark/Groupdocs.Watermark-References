---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지정된 이미지 데이터를 사용하여 PresentationWatermarkableImage 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

지정된 이미지 데이터를 사용하여 [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, image_data):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| image_data | `list[int]` | `PresentationWatermarkableImage`를 생성하는 데 사용되는 부호 없는 바이트 배열입니다. |

### 예시

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### 또 보기
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
