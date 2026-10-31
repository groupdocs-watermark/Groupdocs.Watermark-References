---
title: "get_document_info méthode"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Obtient les informations sur le format du document chargé."
type: docs
url: /fr/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Obtient les informations sur le format du document chargé.

En savoir plus sur l'obtention des informations du document.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### Exemple

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### Voir aussi
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
