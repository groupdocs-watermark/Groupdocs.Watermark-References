---
title: "classe SpreadsheetWatermarkHeaderFooterOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta le opzioni quando si aggiunge la filigrana all'intestazione/piè di pagina di un Spreadsheet."
type: docs
url: /it/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/
is_root: false
weight: 100
---


## SpreadsheetWatermarkHeaderFooterOptions class

Rappresenta le opzioni quando si aggiunge la filigrana all'intestazione/piè di pagina di un Spreadsheet.

Per saperne di più:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

Il tipo SpreadsheetWatermarkHeaderFooterOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/__init__/) | Inizializza una nuova istanza della classe [`SpreadsheetWatermarkHeaderFooterOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/worksheet_index/) | L'indice del foglio di lavoro a cui aggiungere la filigrana. |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Ottiene il valore predefinito per la classe. (ereditato da [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Esempio

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

### Vedi anche
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
