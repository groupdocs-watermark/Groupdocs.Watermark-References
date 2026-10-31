---
title: "Classe PdfXObjectWatermarkOptions"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane XObject à un document PDF."
type: docs
url: /fr/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
is_root: false
weight: 70
---


## PdfXObjectWatermarkOptions class

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane XObject à un document PDF.

En savoir plus :
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

Le type PdfXObjectWatermarkOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/__init__/) | Initialise une nouvelle instance de la classe [`PdfXObjectWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/). |

### Propriétés
| Propriété | Description |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/page_index/) | L’indice de page où ajouter le filigrane. |

### Champs
| Champ | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtient la valeur par défaut pour la classe. (héritée de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfXObjectWatermarkOptions
from groupdocs.watermark.watermarks import ImageWatermark

load_options = PdfLoadOptions()
with Watermarker("./document.pdf", load_options) as watermarker:
    with ImageWatermark("./logo.png") as watermark:
        options = PdfXObjectWatermarkOptions()
        options.page_index = 0  # apply to the first page
        watermarker.add(watermark, options)
    watermarker.save("./output.pdf")
```

### Voir aussi
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
