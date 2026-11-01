---
title: "SpreadsheetWatermarkHeaderFooterOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Geeft opties weer bij het toevoegen van het watermerk aan een Spreadsheet‑kop‑/voettekst."
type: docs
url: /nl/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/
is_root: false
weight: 100
---


## SpreadsheetWatermarkHeaderFooterOptions class

Geeft opties weer bij het toevoegen van het watermerk aan een Spreadsheet‑kop‑/voettekst.

Meer informatie:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

Het type SpreadsheetWatermarkHeaderFooterOptions geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/__init__/) | Initialiseert een nieuw exemplaar van de [`SpreadsheetWatermarkHeaderFooterOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/worksheet_index/) | De index van het werkblad waaraan het watermerk moet worden toegevoegd. |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Haalt de standaardwaarde op voor de klasse. (geërfd van [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetWatermarkHeaderFooterOptions
from groupdocs.watermark.watermarks import Font, TextWatermark
load_options = SpreadsheetLoadOptions()
with Watermarker("./test.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 14))
    options = SpreadsheetWatermarkHeaderFooterOptions()
    options.worksheet_index = 0
    watermarker.add(watermark, options)
    watermarker.save()
```

### Zie ook
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
