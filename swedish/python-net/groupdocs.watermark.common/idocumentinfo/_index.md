---
title: "IDocumentInfo klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Tillhandahåller metoder som krävs för att hämta grundläggande dokumentinformation."
type: docs
url: /sv/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

Tillhandahåller metoder som krävs för att hämta grundläggande dokumentinformation.

Läs mer: Hämta dokumentinformation.

Typen IDocumentInfo exponerar följande medlemmar:

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | Filformatbeskrivningen. |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | Egenskapen indikerar om dokumentet är krypterat och kräver ett lösenord för att öppnas. |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | Det totala sidantalet. |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | Samlingen av beskrivningar av dokumentets sidor. |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | Dokumentets storlek i byte. |

### Exempel

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### Se även
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
