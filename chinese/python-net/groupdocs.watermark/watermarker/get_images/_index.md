---
title: "get_images 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "根据指定的搜索条件查找图像。"
type: docs
url: /zh/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

根据指定的搜索条件查找图像。

搜索在 [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) 中指定的对象中进行。

了解更多关于搜索水印的信息 https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | 要使用的搜索条件。 |

**Returns:** WatermarkableImageCollection: The collection of found images.

### 示例

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

查找文档中的所有图像。

搜索在 [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) 中指定的对象中进行。

了解更多关于搜索水印的信息，位于 https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### 示例

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

        # 文档中嵌入的每个光栅图像
        for image in watermarker.get_images():
            # 跳过诸如图标或项目符号等小图像
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### 另请参见
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
