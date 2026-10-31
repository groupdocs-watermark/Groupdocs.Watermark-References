---
title: "get_document_info μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Ανακτά τις πληροφορίες για ένα έγγραφο που είναι αποθηκευμένο στο συνημμένο αρχείο."
type: docs
url: /el/python-net/groupdocs.watermark.common/attachment/get_document_info/
is_root: false
weight: 1030
---


## get_document_info

Ανακτά τις πληροφορίες για ένα έγγραφο που είναι αποθηκευμένο στο συνημμένο αρχείο.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: An instance that contains detected information.

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    for attachment in content.attachments:
        info = attachment.get_document_info()
        print(f"{attachment.name}: type={info.file_type}")
```

### Δείτε επίσης
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
