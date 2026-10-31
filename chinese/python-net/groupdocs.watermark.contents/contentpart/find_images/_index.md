---
title: "find_images 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "根据指定的搜索条件查找图像。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents/contentpart/find_images/
is_root: false
weight: 1010
---


## find_images {#search_criteria}

根据指定的搜索条件查找图像。搜索在 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) 指定的对象中进行。

```python
def find_images(self, search_criteria):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | 要使用的搜索条件。 |

**Returns:** The collection of the found images.

### 示例

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

在内容中查找所有图像，在 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) 指定的对象中进行搜索。

```python
def find_images(self):
    ...
```

**Returns:** The collection of the found images.

### 示例

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

### 另请参见
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
