---
title: "IDocumentInfo Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt Methoden bereit, die zum Abrufen grundlegender Dokumentinformationen erforderlich sind."
type: docs
url: /de/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

Stellt Methoden bereit, die zum Abrufen grundlegender Dokumentinformationen erforderlich sind.

Mehr erfahren: Dokumentinformationen abrufen.

Der Typ IDocumentInfo stellt die folgenden Mitglieder bereit:

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | Die Dateiformatbeschreibung. |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | Die Eigenschaft gibt an, ob das Dokument verschlüsselt ist und ein Passwort zum Öffnen benötigt. |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | Die Gesamtseitenzahl. |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | Die Sammlung von Beschreibungen der Dokumentseiten. |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | Die Dokumentgröße in Bytes. |

### Beispiel

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### Siehe auch
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
