---
title: "get_document_info-Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Ermittelt die Informationen zum Format des geladenen Dokuments."
type: docs
url: /de/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Ermittelt die Informationen zum Format des geladenen Dokuments.

Erfahren Sie mehr über das Abrufen der Dokumentinformationen.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### Beispiel

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### Siehe auch
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
