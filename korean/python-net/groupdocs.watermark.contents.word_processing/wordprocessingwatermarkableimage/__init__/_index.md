---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지정된 이미지 데이터를 사용하여 WordProcessingWatermarkableImage 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

지정된 이미지 데이터를 사용하여 [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, image_data):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| image_data | `list[int]` | `WordProcessingWatermarkableImage`를 만들기 위한 부호 없는 바이트 배열입니다. |

### 예시

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### 또 보기
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
