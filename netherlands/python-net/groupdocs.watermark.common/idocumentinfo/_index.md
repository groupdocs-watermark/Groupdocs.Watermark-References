---
title: "IDocumentInfo klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Biedt methoden die nodig zijn om basisdocumentinformatie op te halen."
type: docs
url: /nl/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

Biedt methoden die nodig zijn om basisdocumentinformatie op te halen.

Meer info: Documentinformatie ophalen.

Het type IDocumentInfo geeft de volgende leden weer:

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | De bestandsformaatbeschrijving. |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | De eigenschap geeft aan of het document versleuteld is en een wachtwoord vereist om te openen. |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | Het totale aantal pagina's. |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | De verzameling van beschrijvingen van documentpagina's. |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | De documentgrootte in bytes. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### Zie ook
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
