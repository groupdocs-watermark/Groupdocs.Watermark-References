---
title: "get_document_info-metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Hämtar information om formatet för det inlästa dokumentet."
type: docs
url: /sv/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Hämtar information om formatet för det inlästa dokumentet.

Läs mer om att hämta dokumentinformation.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### Exempel

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### Se även
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
