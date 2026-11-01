---
title: "get_document_info-methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Haalt de informatie op over het formaat van het geladen document."
type: docs
url: /nl/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Haalt de informatie op over het formaat van het geladen document.

Meer informatie over het ophalen van de documentinformatie.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### Voorbeeld

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### Zie ook
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
