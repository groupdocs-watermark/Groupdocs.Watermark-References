---
title: "get_document_info μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Λαμβάνει τις πληροφορίες σχετικά με τη μορφή του φορτωμένου εγγράφου."
type: docs
url: /el/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Λαμβάνει τις πληροφορίες σχετικά με τη μορφή του φορτωμένου εγγράφου.

Μάθετε περισσότερα για την λήψη πληροφοριών εγγράφου.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### Παράδειγμα

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### Δείτε επίσης
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
