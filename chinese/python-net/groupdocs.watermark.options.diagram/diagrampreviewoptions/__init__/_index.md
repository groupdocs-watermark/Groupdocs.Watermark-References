---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "初始化 DiagramPreviewOptions 类的新实例，并导致输出流被关闭。"
type: docs
url: /zh/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

初始化 [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/) 类的新实例，并导致输出流被关闭。

```python
def __init__(self, create_page_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 为特定页面预览创建流。 |

## __init__ {#create_page_stream-release_page_stream}

初始化一个新的 [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/) 实例，使输出流返回给客户端以供进一步使用。

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 为特定页面预览创建流。 |
| release_page_stream | `ReleasePageStream` | 通知页面预览生成完成并获取输出流。 |

### 另请参见
* class [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/)
