---
title: "SpreadsheetWatermarkShapeOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Geeft opties weer bij het toevoegen van een vorm‑watermerk aan een Spreadsheet‑werkblad."
type: docs
url: /nl/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/
is_root: false
weight: 120
---


## SpreadsheetWatermarkShapeOptions class

Geeft opties weer bij het toevoegen van een vorm‑watermerk aan een Spreadsheet‑werkblad.

Meer informatie:
- Add watermarks to spreadsheet documents (https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

Het type SpreadsheetWatermarkShapeOptions exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/__init__/) | Initialiseert een nieuw exemplaar van de SpreadsheetWatermarkShapeOptions‑klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [effects](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/effects/) | De effecten die op het watermerk worden toegepast, gespecificeerd als een [`SpreadsheetImageEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/) of [`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/) instantie. |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/worksheet_index/) | De index van het werkblad waaraan het watermerk moet worden toegevoegd. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternative_text/) | De beschrijvende (alternatieve) tekst die aan een vorm wordt gekoppeld. (geërfd van [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/is_locked/) | De eigenschap geeft aan of bewerken van de vorm in Excel verboden is. (geërfd van [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name/) | De naam van de vorm. (geërfd van [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Haalt de standaardwaarde op voor de klasse. (geërfd van [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.spreadsheet import (
    SpreadsheetLoadOptions, SpreadsheetWatermarkShapeOptions,
)

def add_watermark_to_worksheet():
    with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = SpreadsheetWatermarkShapeOptions()
        options.worksheet_index = 0
        watermarker.add(watermark, options)

        watermarker.save("./output.xlsx")
```

### Zie ook
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
