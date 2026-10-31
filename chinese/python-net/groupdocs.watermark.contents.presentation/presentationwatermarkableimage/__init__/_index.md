---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用指定的图像数据初始化 PresentationWatermarkableImage 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

使用指定的图像数据初始化 [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) 类的新实例。

```python
def __init__(self, image_data):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_data | `list[int]` | 用于创建 `PresentationWatermarkableImage` 的无符号字节数组。 |

### 示例

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### 另请参见
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
