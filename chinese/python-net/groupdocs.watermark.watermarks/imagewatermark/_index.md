---
title: "ImageWatermark 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示图像水印。"
type: docs
url: /zh/python-net/groupdocs.watermark.watermarks/imagewatermark/
is_root: false
weight: 40
---


## ImageWatermark class

表示图像水印。

了解更多：
- Adding image watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks

ImageWatermark 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#file_path) | 使用指定的文件路径初始化新的 ImageWatermark 实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#stream) | 使用提供的图像流初始化新的 ImageWatermark。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/dispose/) | 释放当前实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | 指示是否在计算水印大小和坐标时考虑父级边距的属性。如果设置为 True，计算将考虑父级边距；默认情况下该值为 False，父级边距将被忽略。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的期望高度。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | 此 Watermark 的水平对齐方式。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | 指示水印是否应放置在背景中的属性。如果为 true，水印放置在底部；否则放置在顶部（默认是 False）。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | 此 Watermark 的边距设置。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的不透明度。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | 此 Watermark 的页面设置。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的旋转角度（以度为单位）。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | 指示是否将添加的水印信息保存到文档元数据中的属性。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的缩放因子，定义水印大小如何随父级大小而变化。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | 水印的尺寸类型。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | 定义重复水印的选项。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的垂直对齐方式。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的期望宽度。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的 x 坐标。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | 此 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) 的 y 坐标。（继承自 [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)） |

### 示例

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

def add_image_watermark_from_stream():
    # 将图像数据加载到流中
    with open("./logo.png", "rb") as f:
        image_data = f.read()

    # 打开文档并添加图像水印
    with Watermarker("./sample.docx") as watermarker:
        with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
            watermarker.add(watermark)
        watermarker.save("./output.docx")
```

### Guides
使用 `ImageWatermark` 的任务指南：

* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)

### 另请参见
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
