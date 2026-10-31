---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用指定的图像数据初始化 SpreadsheetWatermarkableImage 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

使用指定的图像数据初始化 [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) 类的新实例。

```python
def __init__(self, image_data):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_data | `list[int]` | 用于创建 `SpreadsheetWatermarkableImage` 的无符号字节数组。 |

### 示例

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### 另请参见
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
