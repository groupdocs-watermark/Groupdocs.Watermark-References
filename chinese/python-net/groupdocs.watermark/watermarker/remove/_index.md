---
title: "remove 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "从文档中移除水印。"
type: docs
url: /zh/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

从文档中移除水印。

了解更多关于删除水印的信息：删除已发现的水印。

```python
def remove(self, possible_watermark):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | 要删除的水印。 |

### 示例

```python
from groupdocs.watermark import Watermarker

def remove_first_watermark():
    with Watermarker("./document.pdf") as watermarker:
        watermarks = watermarker.search()
        if watermarks:
            watermarker.remove(watermarks[0])
        watermarker.save("./output.pdf")
```

## remove {#possible_watermarks}

从文档中移除集合中的所有水印。

在 GroupDocs 文档中了解更多关于删除水印的信息。

```python
def remove(self, possible_watermarks):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | 要删除的水印集合。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # 逆序删除以保持索引有效
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### 另请参见
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
