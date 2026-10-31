---
title: "Watermarker 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示文档中水印管理的类。"
type: docs
url: /zh/python-net/groupdocs.watermark/watermarker/
is_root: false
weight: 60
---


## Watermarker class

表示文档中水印管理的类。

加载并保存任何受支持格式的内容。

Watermarker 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path) | 使用指定的文档路径初始化新的 Watermarker 实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-options) | 使用指定的文档路径和加载选项初始化新的 Watermarker 实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-settings) | 使用指定的文档路径和设置初始化 Watermarker。 |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-options-settings) | 使用指定的文档路径、加载选项和设置初始化新的 Watermarker 实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document) | 使用指定的流初始化 Watermarker 类的新实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-options) | 使用指定的流和加载选项初始化新的 Watermarker 实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-settings) | 使用指定的流和设置初始化新的 Watermarker 实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-options-settings) | 使用指定的流、加载选项和设置初始化 [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) 类的新实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark/watermarker/add/#watermark) | 向已加载的文档添加水印。 |
| [add](/watermark/python-net/groupdocs.watermark/watermarker/add/#watermark-options) | 使用水印选项向已加载的文档添加水印。 |
| [add_watermark](/watermark/python-net/groupdocs.watermark/watermarker/add_watermark/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark/watermarker/dispose/) | 释放当前实例。 |
| [generate_preview](/watermark/python-net/groupdocs.watermark/watermarker/generate_preview/#preview_options) | 为文档生成预览图像。 |
| [generate_preview_preview_options](/watermark/python-net/groupdocs.watermark/watermarker/generate_preview_preview_options/) |  |
| [get_content](/watermark/python-net/groupdocs.watermark/watermarker/get_content/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark/watermarker/get_document_info/) | 获取已加载文档格式的信息。 |
| [get_images](/watermark/python-net/groupdocs.watermark/watermarker/get_images/#search_criteria) | 根据指定的搜索条件查找图像。 |
| [get_images](/watermark/python-net/groupdocs.watermark/watermarker/get_images/) | 查找文档中的所有图像。 |
| [get_images_image_search_criteria](/watermark/python-net/groupdocs.watermark/watermarker/get_images_image_search_criteria/) |  |
| [remove](/watermark/python-net/groupdocs.watermark/watermarker/remove/#possible_watermark) | 从文档中移除水印。 |
| [remove](/watermark/python-net/groupdocs.watermark/watermarker/remove/#possible_watermarks) | 从文档中移除集合中的所有水印。 |
| [remove_possible_watermark](/watermark/python-net/groupdocs.watermark/watermarker/remove_possible_watermark/) |  |
| [remove_possible_watermark_collection](/watermark/python-net/groupdocs.watermark/watermarker/remove_possible_watermark_collection/) |  |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/) | 将文档数据保存到底层流。 |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#file_path) | 将文档保存到指定的文件位置。 |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#document) | 将文档保存到指定的流。 |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#options) | 使用保存选项将文档数据保存到底层流。 |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#file_path-options) | 使用保存选项将文档保存到指定的文件位置。 |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#document-options) | 使用保存选项将文档保存到指定的流中。 |
| [save_file](/watermark/python-net/groupdocs.watermark/watermarker/save_file/) |  |
| [save_save_options](/watermark/python-net/groupdocs.watermark/watermarker/save_save_options/) |  |
| [save_stream](/watermark/python-net/groupdocs.watermark/watermarker/save_stream/) |  |
| [save_streams](/watermark/python-net/groupdocs.watermark/watermarker/save_streams/) |  |
| [save_string](/watermark/python-net/groupdocs.watermark/watermarker/save_string/) |  |
| [search](/watermark/python-net/groupdocs.watermark/watermarker/search/) | 搜索文档中所有可能的水印。 |
| [search](/watermark/python-net/groupdocs.watermark/watermarker/search/#search_criteria) | 根据指定的搜索条件搜索可能的水印。 |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark/watermarker/search_search_criteria/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) | 将在水印搜索中包含的对象。 |

### 示例

```python
from groupdocs.watermark import Watermarker

with Watermarker("D:\\input.pdf") as watermarker:
    # 使用 Watermarker 的方法来添加、搜索或移除水印。
    watermarker.save("D:\\output.pdf")
```

### Guides
使用 `Watermarker` 的任务指南：

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)
* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)
* [Document preview](/watermark/python-net/guides/preview/)
* [Get document info](/watermark/python-net/guides/get-document-info/)

### 另请参见
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
