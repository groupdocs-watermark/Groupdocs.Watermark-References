---
title: "SpreadsheetWatermarkModernWordArtOptions klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar alternativ när en modern Word Art‑vattenstämpel läggs till i ett Spreadsheet‑arbetsblad."
type: docs
url: /sv/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/
is_root: false
weight: 110
---


## SpreadsheetWatermarkModernWordArtOptions class

Representerar alternativ när en modern Word Art‑vattenstämpel läggs till i ett Spreadsheet‑arbetsblad.

Läs mer:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

Typen SpreadsheetWatermarkModernWordArtOptions visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/__init__/) | Initierar en ny instans av [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/) klass. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/worksheet_index/) | Indexet för kalkylbladet som vattenstämpeln ska läggas till i. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternative_text/) | Den beskrivande (alternativa) texten som kommer att associeras med en form. (ärvd från [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/is_locked/) | Egenskapen indikerar om redigering av formen i Excel är förbjuden. (ärvd från [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name/) | Namnet på formen. (ärvd från [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |

### Fält
| Fält | Beskrivning |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Hämtar standardvärdet för klassen. (ärvd från [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Exempel

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

### Se även
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
