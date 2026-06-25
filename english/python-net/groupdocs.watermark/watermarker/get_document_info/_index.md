---
title: get_document_info method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Gets information about the format of the loaded document.

Learn more about getting the document information.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### Example

```python
import groupdocs.watermark as gw

with gw.Watermarker("source.docx") as watermarker:
    info = watermarker.get_document_info()
    print("File type:", info.file_type)
    print("Number of pages:", info.page_count)
    print("Document size:", info.size)
```

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
