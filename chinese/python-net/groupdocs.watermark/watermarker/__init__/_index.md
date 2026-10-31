---
title: "__init__ 构造函数"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用指定的文档路径初始化新的 Watermarker 实例。"
type: docs
url: /zh/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

使用指定的文档路径初始化新的 Watermarker 实例。

了解更多关于加载文档的信息： https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 加载文档的文件路径。 |

| 引发 | 描述 |
| :- | :- |
| `UnsupportedFileTypeException` | 提供的文档类型不受支持。 |
| `InvalidPasswordException` | 提供的密码不正确。 |

### 示例

```python
from groupdocs.watermark import Watermarker

# 加载文档。
watermarker = Watermarker("./document.pdf")
# 使用 Watermarker 方法添加、搜索或删除水印。

# 保存文档。
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

使用指定的文档路径和加载选项初始化新的 Watermarker 实例。

了解更多关于加载文档的信息： https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 加载文档的文件路径。 |
| options | `LoadOptions` | 加载文档时使用的其他选项。 |

| 引发 | 描述 |
| :- | :- |
| `UnsupportedFileTypeException` | 提供的文档类型不受支持。 |
| `InvalidPasswordException` | 提供的密码不正确。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # 对加密的 PDF 执行操作
    pass
```

## __init__ {#file_path-settings}

使用指定的文档路径和设置初始化 Watermarker。

了解更多关于加载文档的信息： https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 加载文档的文件路径。 |
| settings | `WatermarkerSettings` | 处理已加载文档时使用的其他设置。 |

| 引发 | 描述 |
| :- | :- |
| `UnsupportedFileTypeException` | 提供的文档类型不受支持。 |
| `InvalidPasswordException` | 提供的密码不正确。 |

### 示例

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import SearchableObjects
from groupdocs.watermark.search.objects import WordProcessingSearchableObjects, SpreadsheetSearchableObjects, PresentationSearchableObjects, DiagramSearchableObjects, PdfSearchableObjects

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
                     | WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=PresentationSearchableObjects.SLIDES_BACKGROUNDS
                  | PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=DiagramSearchableObjects.NONE,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    # 使用 watermarker，例如搜索或移除水印。
    pass
```

## __init__ {#file_path-options-settings}

使用指定的文档路径、加载选项和设置初始化新的 Watermarker 实例。

了解更多关于加载文档的信息： https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 加载文档的文件路径。 |
| options | `LoadOptions` | 加载文档时使用的其他选项。 |
| settings | `WatermarkerSettings` | 处理已加载文档时使用的附加设置。 |

| 引发 | 描述 |
| :- | :- |
| `UnsupportedFileTypeException` | 提供的文档类型不受支持。 |
| `InvalidPasswordException` | 提供的密码不正确。 |

### 示例

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.options.email import EmailLoadOptions
from groupdocs.watermark.search.search_criteria import TextSearchCriteria
from groupdocs.watermark.search.objects import SearchableObjects, EmailSearchableObjects

def search_email():
    settings = WatermarkerSettings()
    settings.searchable_objects = SearchableObjects(
        email_searchable_objects=(
            EmailSearchableObjects.Subject
            | EmailSearchableObjects.HtmlBody
            | EmailSearchableObjects.PlainTextBody
        )
    )
    load_options = EmailLoadOptions()
    with Watermarker("./test.msg", load_options, settings) as watermarker:
        criteria = TextSearchCriteria("test", False)
        watermarks = watermarker.search(criteria)
        watermarks.clear()
        watermarker.save()
```

## __init__ {#document}

使用指定的流初始化 Watermarker 类的新实例。

了解更多关于加载文档的信息： https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 用于加载文档的流。 |

| 引发 | 描述 |
| :- | :- |
| `UnsupportedFileTypeException` | 提供的文档类型不受支持。 |
| `InvalidPasswordException` | 提供的密码不正确。 |

### 示例

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # 使用 Watermarker 的方法来添加、搜索或移除水印。
            watermarker.save(output_stream)
```

## __init__ {#document-options}

使用指定的流和加载选项初始化新的 Watermarker 实例。

了解更多关于加载文档的信息。

```python
def __init__(self, document, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 用于加载文档的流。 |
| options | `LoadOptions` | 加载文档时使用的其他选项。 |

| 引发 | 描述 |
| :- | :- |
| `UnsupportedFileTypeException` | 提供的文档类型不受支持。 |
| `InvalidPasswordException` | 提供的密码不正确。 |

### 示例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # 使用 watermarker 执行操作
        pass
```

## __init__ {#document-settings}

使用指定的流和设置初始化新的 Watermarker 实例。

了解更多关于加载文档的信息。

```python
def __init__(self, document, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 用于加载文档的流。 |
| settings | `WatermarkerSettings` | 处理已加载文档时使用的附加设置。 |

| 引发 | 描述 |
| :- | :- |
| `UnsupportedFileTypeException` | 提供的文档类型不受支持。 |
| `InvalidPasswordException` | 提供的密码不正确。 |

### 示例

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import SearchableObjects
from groupdocs.watermark.search.objects import WordProcessingSearchableObjects, SpreadsheetSearchableObjects, PresentationSearchableObjects, DiagramSearchableObjects, PdfSearchableObjects

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS | WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=PresentationSearchableObjects.SLIDES_BACKGROUNDS | PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=DiagramSearchableObjects.NONE,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

for file_path in ["./document1.pdf", "./document2.docx"]:
    with open(file_path, "rb") as stream:
        with Watermarker(stream, settings) as watermarker:
            watermarks = watermarker.search()
            # 处理已找到的水印
```

## __init__ {#document-options-settings}

使用指定的流、加载选项和设置初始化 [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) 类的新实例。

了解更多关于加载文档的信息，访问 https://docs.groupdocs.com/display/watermarknet/Loading+documents。

```python
def __init__(self, document, options, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| document | `io.RawIOBase` | 用于加载文档的流。 |
| options | `LoadOptions` | 加载文档时使用的其他选项。 |
| settings | `WatermarkerSettings` | 处理已加载文档时使用的其他设置。 |

| 引发 | 描述 |
| :- | :- |
| `UnsupportedFileTypeException` | 提供的文档类型不受支持。 |
| `InvalidPasswordException` | 提供的密码不正确。 |

### 示例

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.options.email import EmailLoadOptions
from groupdocs.watermark.search.objects import SearchableObjects, EmailSearchableObjects
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    email_searchable_objects=(
        EmailSearchableObjects.Subject
        | EmailSearchableObjects.HtmlBody
        | EmailSearchableObjects.PlainTextBody
    )
)

load_options = EmailLoadOptions()
with open("./test.msg", "rb") as stream:
    with Watermarker(stream, load_options, settings) as watermarker:
        criteria = TextSearchCriteria("test", False)
        watermarks = watermarker.search(criteria)
        watermarks.clear()
        watermarker.save("./output.msg")
```

### 另请参见
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
