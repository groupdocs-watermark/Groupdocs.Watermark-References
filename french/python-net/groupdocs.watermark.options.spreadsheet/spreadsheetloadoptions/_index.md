---
title: "classe SpreadsheetLoadOptions"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente les options de chargement de document pour un document Spreadsheet."
type: docs
url: /fr/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/
is_root: false
weight: 40
---


## SpreadsheetLoadOptions class

Représente les options de chargement de document pour un document Spreadsheet.

Le type SpreadsheetLoadOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/) | Initialise une nouvelle instance de la classe [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/#password) | Initialise une nouvelle instance de la classe [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) avec un mot de passe spécifié. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Le type du fichier, indiquant son format (p. ex., docx, pdf, xlsx, etc.). (hérité de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | La famille de format du document, indiquant son type (p. ex., Image, Pdf, Spreadsheet, etc.). (hérité de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Le mot de passe pour ouvrir un document chiffré. (hérité de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Champs
| Champ | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/default/) | Obtient la valeur par défaut pour la classe. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
    # effectuez les opérations de filigrane ici
    pass
```

### Voir aussi
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
