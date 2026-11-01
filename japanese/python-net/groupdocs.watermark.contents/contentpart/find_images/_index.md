---
title: "find_images メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "指定された検索条件に従って画像を検索します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents/contentpart/find_images/
is_root: false
weight: 1010
---


## find_images {#search_criteria}

指定された検索条件に従って画像を検索します。検索は[`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) で指定されたオブジェクト内で実行されます。

```python
def find_images(self, search_criteria):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | 使用する検索条件です。 |

**Returns:** The collection of the found images.

### 例

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

コンテンツ内のすべての画像を検索し、[`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) で指定されたオブジェクト内を対象とします。

```python
def find_images(self):
    ...
```

**Returns:** The collection of the found images.

### 例

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

### 関連項目
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
