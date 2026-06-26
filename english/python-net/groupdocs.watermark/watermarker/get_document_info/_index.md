---
title: get_document_info method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Gets the information about the format of the loaded document."
type: docs
url: /python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Gets the information about the format of the loaded document.

Learn more about getting the document information.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An object that contains detected information such as file type, page count, and size.

### Example

```python
import io
import groupdocs.watermark as gw

with open("source.docx", "rb") as f:
    stream = io.BytesIO(f.read())

with gw.Watermarker(stream) as watermarker:
    info = watermarker.get_document_info()
    print("File type:", info.file_type)
    print("Number of pages:", info.page_count)
    print("Document size:", info.size)
```

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
