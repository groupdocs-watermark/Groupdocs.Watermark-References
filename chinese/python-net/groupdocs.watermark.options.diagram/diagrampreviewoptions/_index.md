---
title: "DiagramPreviewOptions 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "提供用于设置 Diagram 文档预览生成的需求和流委托的选项。"
type: docs
url: /zh/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/
is_root: false
weight: 30
---


## DiagramPreviewOptions class

提供用于设置 Diagram 文档预览生成的需求和流委托的选项。

DiagramPreviewOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/__init__/#create_page_stream) | 初始化 [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/) 类的新实例，并导致输出流被关闭。 |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/__init__/#create_page_stream-release_page_stream) | 初始化一个新的 [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/) 实例，使输出流返回给客户端以供进一步使用。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [high_quality_rendering](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/high_quality_rendering/) | 用于高质量渲染的标志。 |
| [resolution](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/resolution/) | 生成图像的分辨率，以每英寸点数表示。 |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | 用于获取每个渲染页面的可写流的页面流创建委托。（继承自 [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)） |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | 页面预览高度。（继承自 [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)） |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | 用于生成预览的页码数组。（继承自 [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)） |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | 预览图像格式。（继承自 [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)） |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | 页面预览完成委托。（继承自 [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)） |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | 页面预览宽度。（继承自 [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)） |

### 字段
| 字段 | 描述 |
| :- | :- |
| [DEFAULT_RESOLUTION](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/default_resolution/) | 默认分辨率，以每英寸点数表示。 |

### 另请参见
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
