---
title: "Classe DiagramPageWatermarkOptions"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane de forme à une page particulière d'un document Visio."
type: docs
url: /fr/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
is_root: false
weight: 20
---


## DiagramPageWatermarkOptions class

Représente les options d'ajout de filigrane lors de l'ajout d'un filigrane de forme à une page particulière d'un document Visio.

En savoir plus :
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents

Le type DiagramPageWatermarkOptions expose les membres suivants:

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/__init__/) | Initialise une nouvelle instance de la classe [`DiagramPageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/). |

### Propriétés
| Propriété | Description |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/page_index/) | L’indice de page où ajouter le filigrane. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/is_locked/) | La propriété indique si la modification de la forme dans Visio est interdite. (héritée de [`DiagramWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/)) |

### Champs
| Champ | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtient la valeur par défaut pour la classe. (héritée de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.diagram import DiagramPageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./diagram.vsdx") as watermarker:
    watermark = TextWatermark("watermark test", Font("Arial", 42.0))

    options = DiagramPageWatermarkOptions()
    options.is_locked = True
    options.page_index = 0

    watermarker.add(watermark, options)
    watermarker.save("./output.vsdx")
```

### Voir aussi
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
