---
title: "SpreadsheetImageEffects klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt effecten voor die kunnen worden toegepast op een afbeeldingswatermerk voor een Excel-document."
type: docs
url: /nl/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/
is_root: false
weight: 30
---


## SpreadsheetImageEffects class

Stelt effecten voor die kunnen worden toegepast op een afbeeldingswatermerk voor een Excel-document.

Het type SpreadsheetImageEffects bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/__init__/) | Initialiseert een nieuw exemplaar van de [`SpreadsheetImageEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | De lijnopmaakinstellingen voor de afbeeldingsrand. (geërfd van [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | De helderheid van de afbeelding. Moet een float zijn tussen 0.0 (donkerst) en 1.0 (helderst). De standaardwaarde is 0.5. (geërfd van [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | De kleurwaarde van de afbeelding die als transparant wordt behandeld. De standaardwaarde is een volledig transparante kleur. (geërfd van [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | Het contrast voor de opgegeven afbeelding. Moet een float zijn tussen 0.0 (minst contrast) en 1.0 (meest contrast). De standaardwaarde is 0.5. (geërfd van [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | De eigenschap geeft aan of een afbeelding in grijstintenmodus wordt weergegeven. (geërfd van [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |

### Voorbeeld

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls

load_options = gwo_xls.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    with gww.ImageWatermark("logo.png") as watermark:
        effects = gwo_xls.SpreadsheetImageEffects()
        effects.brightness = 0.7
        effects.contrast = 0.6
        effects.chroma_key = gww.Color.red
        effects.border_line_format.enabled = True
        effects.border_line_format.weight = 1
        options = gwo_xls.SpreadsheetWatermarkShapeOptions()
        options.effects = effects
        watermarker.add(watermark, options)
    watermarker.save("output.xlsx")
```

### Zie ook
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
