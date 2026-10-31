---
title: "IDocumentInfo 类"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "提供检索基本文档信息所需的方法。"
type: docs
url: /zh/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

提供检索基本文档信息所需的方法。

了解更多：获取文档信息。

IDocumentInfo 类型公开以下成员：

### 属性
| 属性 | 描述 |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | 文件格式描述。 |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | 该属性指示文档是否已加密以及是否需要密码打开。 |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | 总页数。 |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | 文档页面描述的集合。 |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | 文档大小（字节）。 |

### 示例

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### 另请参见
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
