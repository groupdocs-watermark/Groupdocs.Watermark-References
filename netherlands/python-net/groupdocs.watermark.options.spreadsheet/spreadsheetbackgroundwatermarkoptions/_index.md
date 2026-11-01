---
title: "SpreadsheetBackgroundWatermarkOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt opties voor wanneer het watermerk als achtergrond aan een Spreadsheet-werkblad wordt toegevoegd."
type: docs
url: /nl/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
is_root: false
weight: 20
---


## SpreadsheetBackgroundWatermarkOptions class

Stelt opties voor wanneer het watermerk als achtergrond aan een Spreadsheet-werkblad wordt toegevoegd.

Meer informatie: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

Het type SpreadsheetBackgroundWatermarkOptions bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/__init__/) | Initialiseert een nieuw exemplaar van de [`SpreadsheetBackgroundWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [background_height](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_height/) | De gewenste hoogte van de achtergrondafbeelding in pixels. |
| [background_width](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_width/) | De gewenste breedte van de achtergrondafbeelding in pixels. |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheet_index/) | De index van het werkblad waaraan het watermerk moet worden toegevoegd. |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Haalt de standaardwaarde op voor de klasse. (geërfd van [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetBackgroundWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = SpreadsheetLoadOptions()
with Watermarker(r"C:\Documents\test.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36))

    options = SpreadsheetBackgroundWatermarkOptions()
    options.worksheet_index = -1  # default
    options.background_width = 800
    options.background_height = 600

    watermarker.add(watermark, options)
    watermarker.save()
```

### Zie ook
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
