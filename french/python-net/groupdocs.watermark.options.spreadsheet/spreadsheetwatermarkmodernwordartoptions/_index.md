---
title: "SpreadsheetWatermarkModernWordArtOptions classe"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente les options lors de l'ajout d'un filigrane moderne de Word Art à une feuille de calcul Spreadsheet."
type: docs
url: /fr/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/
is_root: false
weight: 110
---


## SpreadsheetWatermarkModernWordArtOptions class

Représente les options lors de l'ajout d'un filigrane moderne de Word Art à une feuille de calcul Spreadsheet.

En savoir plus :
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

Le type SpreadsheetWatermarkModernWordArtOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/__init__/) | Initialise une nouvelle instance de la classe [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/). |

### Propriétés
| Propriété | Description |
| :- | :- |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/worksheet_index/) | L'index de la feuille de calcul où ajouter le filigrane. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternative_text/) | Le texte descriptif (alternatif) qui sera associé à une forme. (hérité de [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/is_locked/) | La propriété indique si la modification de la forme dans Excel est interdite. (hérité de [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name/) | Le nom de la forme. (hérité de [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |

### Champs
| Champ | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtient la valeur par défaut pour la classe. (héritée de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetWatermarkModernWordArtOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = SpreadsheetLoadOptions()
with Watermarker("./spreadsheet.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36.0))
    options = SpreadsheetWatermarkModernWordArtOptions()
    options.worksheet_index = 0
    options.is_locked = False
    watermarker.add(watermark, options)
    watermarker.save("./output.xlsx")
```

### Voir aussi
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
