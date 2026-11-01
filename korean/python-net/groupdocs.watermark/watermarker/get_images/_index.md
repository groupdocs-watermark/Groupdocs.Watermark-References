---
title: "get_images 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지정된 검색 기준에 따라 이미지를 찾습니다."
type: docs
url: /ko/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

지정된 검색 기준에 따라 이미지를 찾습니다.

검색은 [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/)에 지정된 객체에서 수행됩니다.

워터마크 검색에 대해 자세히 알아보려면 https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | 사용할 검색 기준. |

**Returns:** WatermarkableImageCollection: The collection of found images.

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType

with Watermarker("./document.pdf") as watermarker:
    watermark = TextWatermark("PROTECTED", Font("Arial", 8.0))
    watermark.foreground_color = Color.red
    watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS

    for image in watermarker.get_images():
        if image.width > 100 and image.height > 100:
            image.add(watermark)

    watermarker.save("./output.pdf")
```

## get_images

문서 내 모든 이미지를 찾습니다.

검색은 [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/)에 지정된 객체에서 수행됩니다.

https://docs.groupdocs.com/display/watermarknet/Searching+watermarks 에서 워터마크 검색에 대해 자세히 알아보세요.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.options.pdf import PdfLoadOptions

def watermark_images_inside():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        watermark = TextWatermark("PROTECTED", Font("Arial", 8.0))
        watermark.foreground_color = Color.red
        watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS
        watermark.scale_factor = 1.0

        # 문서에 삽입된 모든 래스터 이미지
        for image in watermarker.get_images():
            # 아이콘이나 글머리표와 같은 작은 이미지는 건너뛰세요
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### 또 보기
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
