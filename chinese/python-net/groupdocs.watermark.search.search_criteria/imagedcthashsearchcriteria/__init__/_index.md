---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用指定的文件路径初始化 ImageDctHashSearchCriteria 实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

使用指定的文件路径初始化 ImageDctHashSearchCriteria 实例。

```python
def __init__(self, file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 加载图像的文件路径。 |

### 示例

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

使用提供的图像流初始化 ImageDctHashSearchCriteria 实例。

```python
def __init__(self, stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 加载图像的流。 |

### 另请参见
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
