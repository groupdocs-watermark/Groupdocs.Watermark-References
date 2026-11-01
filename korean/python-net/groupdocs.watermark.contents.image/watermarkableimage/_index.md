---
title: "WatermarkableImage 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "문서 내부의 이미지를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.image/watermarkableimage/
is_root: false
weight: 90
---


## WatermarkableImage class

문서 내부의 이미지를 나타냅니다.

자세히 알아보기:
- https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document

WatermarkableImage 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/#watermark) | 이 [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)에 워터마크를 추가합니다. 이 메서드는 워터마크 오프셋과 크기가 픽셀 단위로 측정된다고 가정합니다(할당된 경우). |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) |  |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | 이미지를 바이트 배열로 가져옵니다. |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 지정된 검색 기준에 따라 이미지를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 지정된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 지정된 검색 기준에 따라 가능한 워터마크를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 나열된 객체에서 수행됩니다. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | 이 [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)의 높이(픽셀 단위)입니다. |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | 이 WatermarkableImage의 너비(픽셀 단위)입니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker(r"D:\input.doc") as watermarker:
    # 텍스트 워터마크를 초기화합니다.
    watermark = TextWatermark("DRAFT", Font("Arial", 19))

    # 문서에서 모든 이미지를 찾습니다.
    images = watermarker.get_images()

    # 각 이미지에 워터마크를 추가합니다.
    for img in images:
        img.add(watermark)

    # 변경 사항을 저장합니다.
    watermarker.save(r"D:\output.doc")
```

### 또 보기
* module [`groupdocs.watermark.contents.image`](/watermark/python-net/groupdocs.watermark.contents.image/)
