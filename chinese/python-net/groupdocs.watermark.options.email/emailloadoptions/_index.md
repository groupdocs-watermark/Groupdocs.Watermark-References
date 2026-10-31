---
title: "EmailLoadOptions 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "表示电子邮件消息的文档加载选项。"
type: docs
url: /zh/python-net/groupdocs.watermark.options.email/emailloadoptions/
is_root: false
weight: 10
---


## EmailLoadOptions class

表示电子邮件消息的文档加载选项。

EmailLoadOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/) | 初始化 [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/) 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | 文件的类型，指示其格式（例如 docx、pdf、xlsx 等）。（继承自 [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)） |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | 文档的格式族，指示其类型（例如 Image、Pdf、Spreadsheet 等）。（继承自 [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)） |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | 打开加密文档的密码。（继承自 [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)） |

### 字段
| 字段 | 描述 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/default/) | 获取类的默认值。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # 在此操作电子邮件内容
    watermarker.save("./output.msg")
```

### 另请参见
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
