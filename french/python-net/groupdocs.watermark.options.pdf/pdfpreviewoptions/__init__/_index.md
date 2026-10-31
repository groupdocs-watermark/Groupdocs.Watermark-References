---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de la classe PdfPreviewOptions qui ferme le flux de sortie."
type: docs
url: /fr/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialise une nouvelle instance de la classe [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/) qui ferme le flux de sortie.

```python
def __init__(self, create_page_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Crée un flux pour un aperçu de page spécifique. |

## __init__ {#create_page_stream-release_page_stream}

Initialise une nouvelle instance de PdfPreviewOptions qui renvoie le flux de sortie au client pour une utilisation ultérieure.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Crée un flux pour un aperçu de page spécifique. |
| release_page_stream | `ReleasePageStream` | Notifie que la génération de l'aperçu de page est terminée et obtient le flux de sortie. |

### Voir aussi
* class [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/)
