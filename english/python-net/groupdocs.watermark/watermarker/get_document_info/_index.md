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

**Returns:** IDocumentInfo: The instance that contains detected information.

### Example

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
