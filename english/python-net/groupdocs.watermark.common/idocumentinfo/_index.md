---
title: IDocumentInfo class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Provides methods required for retrieving basic document information."
type: docs
url: /python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

Provides methods required for retrieving basic document information.

Learn more

- [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

The IDocumentInfo type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | The file format description. |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | The document is encrypted and requires a password to open; returns True if encrypted, otherwise False. |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | The total page count. |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | The collection of document pages descriptions. |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | The document size in bytes. |

### Example

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format}")
    print(f"Document contains {doc_info.page_count} pages")
```

### See Also
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
