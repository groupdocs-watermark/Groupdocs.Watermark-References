---
title: "get_images メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "指定された検索条件に従って画像を検索します。"
type: docs
url: /ja/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

指定された検索条件に従って画像を検索します。

検索は、[`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) で指定されたオブジェクト内で実行されます。

透かしの検索について詳しくは https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | 使用する検索条件です。 |

**Returns:** WatermarkableImageCollection: The collection of found images.

### 例

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

ドキュメント内のすべての画像を検索します。

検索は、[`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) で指定されたオブジェクト内で実行されます。

透かしの検索について詳しくは https://docs.groupdocs.com/display/watermarknet/Searching+watermarks にて。

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### 例

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

        # ドキュメントに埋め込まれたすべてのラスター画像
        for image in watermarker.get_images():
            # アイコンや箇条書き記号などの小さな画像はスキップします
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### 関連項目
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
