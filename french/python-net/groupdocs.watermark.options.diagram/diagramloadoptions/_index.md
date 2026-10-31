---
title: "Classe DiagramLoadOptions"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente les options de chargement du document pour un document Visio."
type: docs
url: /fr/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/
is_root: false
weight: 10
---


## DiagramLoadOptions class

Représente les options de chargement du document pour un document Visio.

Le type DiagramLoadOptions expose les membres suivants:

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/) | Initialise une nouvelle instance de la classe [`DiagramLoadOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/#password) | Initialise une nouvelle instance de la classe [`DiagramLoadOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/) avec un mot de passe spécifié. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Le type du fichier, indiquant son format (p. ex., docx, pdf, xlsx, etc.). (hérité de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | La famille de format du document, indiquant son type (p. ex., Image, Pdf, Spreadsheet, etc.). (hérité de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Le mot de passe pour ouvrir un document chiffré. (hérité de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Champs
| Champ | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/default/) | Obtient la valeur par défaut pour la classe. |

### Exemple

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.diagram import DiagramLoadOptions
import groupdocs.watermark.contents.diagram as gwc_vsdx

load_options = DiagramLoadOptions()
with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
    content = watermarker.get_content()
    # manipulez les formes ici
    watermarker.save("output.vsdx")
```

### Voir aussi
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
