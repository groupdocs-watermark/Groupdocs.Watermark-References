---
title: "DiagramWatermarkableImage 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示 Visio 文档内的图像。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/
is_root: false
weight: 130
---


## DiagramWatermarkableImage class

表示 Visio 文档内的图像。

DiagramWatermarkableImage 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/#image_data) | 使用指定的图像数据初始化 [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) 类的新实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/) | 向此 [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) 添加水印。此方法假设水印的偏移量和大小以像素为单位（如果已分配）。（继承自 [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)） |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) | （继承自 [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)） |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | 根据指定的搜索条件查找图像。搜索在 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) 指定的对象中进行。(inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | 获取图像的字节数组。（继承自 [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)） |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | 根据指定的搜索条件查找可能的水印。搜索在 [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) 列出的对象上执行。(inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### 属性
| 属性 | 描述 |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | 此 [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) 的高度（像素）。（继承自 [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)） |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | 此 WatermarkableImage 的宽度（像素）。（继承自 [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)） |

### 示例

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.diagram import DiagramLoadOptions
import groupdocs.watermark.contents.diagram as gwc_vsdx

load_options = DiagramLoadOptions()
with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
    content = watermarker.get_content()
    for shape in content.pages[0].shapes:
        if shape.image is not None:
            with open("test.png", "rb") as f:
                shape.image = gwc_vsdx.DiagramWatermarkableImage(f.read())
    watermarker.save("output.vsdx")
```

### 另请参见
* module [`groupdocs.watermark.contents.diagram`](/watermark/python-net/groupdocs.watermark.contents.diagram/)
