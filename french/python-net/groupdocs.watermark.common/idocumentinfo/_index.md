---
title: "Classe IDocumentInfo"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Fournit les méthodes requises pour récupérer les informations de base du document."
type: docs
url: /fr/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

Fournit les méthodes requises pour récupérer les informations de base du document.

En savoir plus : Obtenir les informations du document.

Le type IDocumentInfo expose les membres suivants:

### Propriétés
| Propriété | Description |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | La description du format de fichier. |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | La propriété indique si le document est chiffré et nécessite un mot de passe pour l'ouvrir. |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | Le nombre total de pages. |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | La collection des descriptions des pages du document. |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | La taille du document en octets. |

### Exemple

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### Voir aussi
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
