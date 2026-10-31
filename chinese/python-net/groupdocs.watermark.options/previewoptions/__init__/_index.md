---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "初始化一个在使用后关闭输出流的 PreviewOptions 实例。"
type: docs
url: /zh/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

初始化一个在使用后关闭输出流的 PreviewOptions 实例。

```python
def __init__(self, create_page_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – 为特定页面预览创建流。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # 为每个要渲染的页面提供可写文件流
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

## __init__ {#create_page_stream-release_page_stream}

初始化一个将输出流返回给客户端以供进一步使用的 PreviewOptions 实例。

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 用于为特定页面预览创建流的 Callable。接收页面编号（`int`），并应返回可写流（`io.RawIOBase`）。 |
| release_page_stream | `ReleasePageStream` | 在页面预览生成完成时调用的 Callable，并提供输出流。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # 为每个要渲染的页面提供可写文件流
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### 另请参见
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
