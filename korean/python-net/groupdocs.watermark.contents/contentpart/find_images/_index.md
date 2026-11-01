---
title: "find_images 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지정된 검색 기준에 따라 이미지를 찾습니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents/contentpart/find_images/
is_root: false
weight: 1010
---


## find_images {#search_criteria}

지정된 검색 기준에 따라 이미지를 찾습니다. 검색은 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 지정된 객체에서 수행됩니다.

```python
def find_images(self, search_criteria):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | 사용할 검색 기준. |

**Returns:** The collection of the found images.

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    watermark = TextWatermark("Protected image", Font("Arial", 8.0))
    content = watermarker.get_content()
    for image in content.sections[0].find_images():
        image.add(watermark)
    watermarker.save("./output.docx")
```

## find_images

콘텐츠 내 모든 이미지를 찾으며, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/)에 지정된 객체를 검색합니다.

```python
def find_images(self):
    ...
```

**Returns:** The collection of the found images.

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    watermark = TextWatermark("Protected image", Font("Arial", 8.0))
    content = watermarker.get_content()
    for image in content.sections[0].find_images():
        image.add(watermark)
    watermarker.save("./output.docx")
```

### 또 보기
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
