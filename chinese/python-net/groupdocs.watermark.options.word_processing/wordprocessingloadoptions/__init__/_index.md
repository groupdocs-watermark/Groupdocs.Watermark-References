---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "初始化 WordProcessingLoadOptions 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

初始化 [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) 类的新实例。

```python
def __init__(self):
    ...
```

## __init__ {#password}

使用指定密码初始化 WordProcessingLoadOptions 类的新实例。

```python
def __init__(self, password):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| password | `str` | 用于打开加密内容的密码。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # 执行水印操作
    pass
```

### 另请参见
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
