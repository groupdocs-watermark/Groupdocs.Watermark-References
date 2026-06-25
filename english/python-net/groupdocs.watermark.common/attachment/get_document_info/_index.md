---
title: get_document_info method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

Gets the information about a document stored in the attached file.

```python
def get_document_info(self):
    ...
```

**Returns:** `IDocumentInfo`: Instance that contains detected information.

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf

with gw.Watermarker("document.pdf", gw.PdfLoadOptions()) as watermarker:
    pdf_content = watermarker.get_content(gwc_pdf.PdfContent)
    for attachment in pdf_content.attachments:
        info = attachment.get_document_info()
        print(info.file_type, info.is_encrypted)
```

### See Also
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
