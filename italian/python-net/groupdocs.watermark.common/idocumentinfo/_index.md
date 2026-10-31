---
title: "IDocumentInfo classe"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Fornisce i metodi necessari per recuperare le informazioni di base del documento."
type: docs
url: /it/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

Fornisce i metodi necessari per recuperare le informazioni di base del documento.

Per saperne di più: Ottieni informazioni sul documento.

Il tipo IDocumentInfo espone i seguenti membri:

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | La descrizione del formato file. |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | La proprietà indica se il documento è crittografato e richiede una password per l'apertura. |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | Il conteggio totale delle pagine. |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | La raccolta delle descrizioni delle pagine del documento. |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | La dimensione del documento in byte. |

### Esempio

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### Vedi anche
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
