---
title: "SpreadsheetLoadOptions-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar alternativ för dokumentladdning för ett Spreadsheet-dokument."
type: docs
url: /sv/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/
is_root: false
weight: 40
---


## SpreadsheetLoadOptions class

Representerar alternativ för dokumentladdning för ett Spreadsheet-dokument.

SpreadsheetLoadOptions-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/) | Initierar en ny instans av klassen [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) . |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/#password) | Initierar en ny instans av klassen [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) med ett angivet lösenord. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Filens typ, som anger dess format (t.ex. docx, pdf, xlsx, osv.). (ärvd från [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Formatfamiljen för dokumentet, som anger dess typ (t.ex. Image, Pdf, Spreadsheet, osv.). (ärvd från [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Lösenordet för att öppna ett krypterat dokument. (ärvd från [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Fält
| Fält | Beskrivning |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/default/) | Hämtar standardvärdet för klassen. |

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
    # utför vattenstämpeloperationer här
    pass
```

### Se även
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
