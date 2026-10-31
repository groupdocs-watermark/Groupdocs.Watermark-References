---
title: "SpreadsheetBackgroundWatermarkOptions Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt Optionen dar, wenn das Wasserzeichen als Hintergrund zu einem Spreadsheet‑Arbeitsblatt hinzugefügt wird."
type: docs
url: /de/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
is_root: false
weight: 20
---


## SpreadsheetBackgroundWatermarkOptions class

Stellt Optionen dar, wenn das Wasserzeichen als Hintergrund zu einem Spreadsheet‑Arbeitsblatt hinzugefügt wird.

Mehr erfahren: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

Der Typ SpreadsheetBackgroundWatermarkOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/__init__/) | Initialisiert eine neue Instanz der [`SpreadsheetBackgroundWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/) Klasse. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [background_height](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_height/) | Die gewünschte Höhe des Hintergrundbildes in Pixeln. |
| [background_width](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_width/) | Die gewünschte Breite des Hintergrundbildes in Pixeln. |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheet_index/) | Der Index des Arbeitsblatts, zu dem das Wasserzeichen hinzugefügt werden soll. |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Ermittelt den Standardwert für die Klasse. (geerbt von [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Beispiel

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

### Siehe auch
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
