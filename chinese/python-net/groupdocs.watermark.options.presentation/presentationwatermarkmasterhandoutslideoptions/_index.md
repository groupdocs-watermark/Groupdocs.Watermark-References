---
title: "PresentationWatermarkMasterHandoutSlideOptions 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示在向 Presentation 文档母版讲义幻灯片添加水印时的选项。"
type: docs
url: /zh/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterhandoutslideoptions/
is_root: false
weight: 90
---


## PresentationWatermarkMasterHandoutSlideOptions class

表示在向 Presentation 文档母版讲义幻灯片添加水印时的选项。

了解更多：
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

请参阅 [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/) 中的使用示例。

PresentationWatermarkMasterHandoutSlideOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterhandoutslideoptions/__init__/) | 初始化 [`PresentationWatermarkMasterHandoutSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterhandoutslideoptions/) 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | 描述性的（替代）文本将与形状关联。（继承自 [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)） |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | 要应用于水印的效果，指定为 [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) 或 [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/) 实例。（继承自 [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)） |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | 该属性指示是否禁止在 PowerPoint 中编辑形状。（继承自 [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)） |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | 形状的名称。（继承自 [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)） |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | 该属性指示文本水印字符是否与不可读字符混合。（继承自 [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)） |

### 字段
| 字段 | 描述 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | 获取类的默认值。（继承自 [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)） |

### 示例

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.presentation as gwo_ppt
import groupdocs.watermark.contents.presentation as gwc_ppt

load_options = gwo_ppt.PresentationLoadOptions()
with gw.Watermarker("presentation.pptx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))
    handout_opts = gwo_ppt.PresentationWatermarkMasterHandoutSlideOptions()
    watermarker.add(watermark, handout_opts)
```

### 另请参见
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
