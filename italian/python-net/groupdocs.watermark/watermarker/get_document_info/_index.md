---
title: "metodo get_document_info"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Ottiene le informazioni sul formato del documento caricato."
type: docs
url: /it/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Ottiene le informazioni sul formato del documento caricato.

Maggiori informazioni sull'ottenimento delle informazioni del documento.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### Esempio

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### Vedi anche
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
