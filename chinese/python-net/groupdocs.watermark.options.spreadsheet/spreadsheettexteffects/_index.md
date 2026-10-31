---
title: "SpreadsheetTextEffects 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示可应用于 Excel 文档文本水印的效果。"
type: docs
url: /zh/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/
is_root: false
weight: 80
---


## SpreadsheetTextEffects class

表示可应用于 Excel 文档文本水印的效果。

SpreadsheetTextEffects 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/__init__/) | 初始化 [`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/) 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [line_format](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/line_format/) | 线格式设置，由一个 [`OfficeLineFormat`](/watermark/python-net/groupdocs.watermark.contents/officelineformat/) 实例表示。（继承自 [`OfficeTextEffects`](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/)） |

### 示例

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls
import groupdocs.watermark.common as gwc
from groupdocs.watermark.contents import OfficeDashStyle, OfficeLineStyle

load_options = gwo_xls.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Segoe UI", 19.0))
    effects = gwo_xls.SpreadsheetTextEffects()
    effects.line_format.enabled = True
    effects.line_format.color = gww.Color.red
    effects.line_format.dash_style = OfficeDashStyle.DASH_DOT_DOT
    effects.line_format.line_style = OfficeLineStyle.TRIPLE
    effects.line_format.weight = 1
    options = gwo_xls.SpreadsheetWatermarkShapeOptions()
    options.effects = effects
    watermarker.add(watermark, options)
    watermarker.save("output.xlsx")
```

### 另请参见
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
