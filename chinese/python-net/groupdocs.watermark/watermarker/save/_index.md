---
title: "save 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "将文档数据保存到底层流。"
type: docs
url: /zh/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

将文档数据保存到底层流。

了解更多关于保存文档的信息: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker(r"D:\\test.msg") as watermarker:
    criteria = TextSearchCriteria("test", False)
    watermarks = watermarker.search(criteria)
    watermarker.remove(watermarks)
    watermarker.save()
```

## save {#file_path}

将文档保存到指定的文件位置。

了解更多关于保存文档的信息: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 用于保存文档数据的文件路径。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

def add_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)
        watermarker.save("output.pdf")
```

## save {#document}

将文档保存到指定的流。

了解更多关于保存文档的信息，位于 https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, document):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 用于保存文档数据的流。 |

### 示例

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    stream = BytesIO()
    watermarker.save(stream)
    # `stream` 现在包含已保存的 PDF 字节
```

## save {#options}

使用保存选项将文档数据保存到底层流。

了解更多关于保存文档的信息。

```python
def save(self, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | `SaveOptions` | 保存文档时使用的其他选项。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save(SaveOptions())
```

## save {#file_path-options}

使用保存选项将文档保存到指定的文件位置。

了解更多关于保存文档的信息: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 用于保存文档数据的文件路径。 |
| options | `SaveOptions` | 保存文档时使用的其他选项。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font
from groupdocs.watermark.options import SaveOptions

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save("output.pdf", SaveOptions())
```

## save {#document-options}

使用保存选项将文档保存到指定的流中。

了解更多关于保存文档的信息，位于 GroupDocs 文档中。

```python
def save(self, document, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 用于保存文档数据的流。 |
| options | `SaveOptions` | 保存文档时使用的其他选项。 |

### 示例

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

def add_watermark_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)

        stream = BytesIO()
        watermarker.save(stream, SaveOptions())
        # stream 现在包含已保存的 PDF 数据
        # 例如，写入文件
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### 另请参见
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
