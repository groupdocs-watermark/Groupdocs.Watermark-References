---
title: "ImageInpaintingPossibleWatermark 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示手动指定的图像区域，应进行修复（使用周围像素填充）."
type: docs
url: /zh/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
is_root: false
weight: 110
---


## ImageInpaintingPossibleWatermark class

表示手动指定的图像区域，应进行修复（使用周围像素填充）.

ImageInpaintingPossibleWatermark 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/__init__/) | 初始化一个新的 ImageInpaintingPossibleWatermark 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [method](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method/) | 用于可能水印检测的修复算法。默认是 `InpaintingMethod.patch_based`。 |
| [parent](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent/) | 此 ImageInpaintingPossibleWatermark 的父对象。始终返回 None，因为区域是手动指定的。 |
| [patch_size](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patch_size/) | 算法使用的补丁大小（奇数，5-11）。 |
| [polygons](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons/) | 待修复的多边形区域，以多边形列表表示，每个多边形是图像像素坐标的顶点列表。 |
| [rectangles](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles/) | 待修复的矩形区域（图像像素）。 |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | 此 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) 的格式化文本片段集合。（继承自 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)） |
| [height](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/height/) | 此 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) 的高度。（继承自 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)） |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | 此 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) 的图像；如果水印没有图像则为 None。（继承自 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)） |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | 放置水印的页码。（继承自 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)） |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/rotate_angle/) | 此 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) 的旋转角度（单位：度）。（继承自 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)） |
| [text](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/text/) | 此 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) 的文本。（继承自 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)） |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/unit_of_measurement/) | 此 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) 的计量单位。（继承自 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)） |
| [width](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/width/) | 此 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) 的宽度。（继承自 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)） |
| [x](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/x/) | 此 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) 的 X 坐标。（继承自 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)） |
| [y](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/y/) | 此 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) 的 Y 坐标。（继承自 [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)） |

### 另请参见
* module [`groupdocs.watermark.search.watermarks`](/watermark/python-net/groupdocs.watermark.search.watermarks/)
