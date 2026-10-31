---
title: "SpreadsheetLoadOptions 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示电子表格文档的加载选项。"
type: docs
url: /zh/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/
is_root: false
weight: 40
---


## SpreadsheetLoadOptions class

表示电子表格文档的加载选项。

SpreadsheetLoadOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/) | 初始化 [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) 类的新实例。 |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/#password) | 使用指定密码初始化 [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | 文件的类型，指示其格式（例如 docx、pdf、xlsx 等）。（继承自 [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)） |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | 文档的格式族，指示其类型（例如 Image、Pdf、Spreadsheet 等）。（继承自 [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)） |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | 打开加密文档的密码。（继承自 [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)） |

### 字段
| 字段 | 描述 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/default/) | 获取该类的默认值。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
    # 在此执行水印操作
    pass
```

### 另请参见
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
