---
title: "SpreadsheetLoadOptions Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt Optionen zum Laden von Dokumenten für ein Spreadsheet‑Dokument dar."
type: docs
url: /de/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/
is_root: false
weight: 40
---


## SpreadsheetLoadOptions class

Stellt Optionen zum Laden von Dokumenten für ein Spreadsheet‑Dokument dar.

Der Typ SpreadsheetLoadOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/) | Initialisiert eine neue Instanz der [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) Klasse. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/__init__/#password) | Initialisiert eine neue Instanz der [`SpreadsheetLoadOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/) Klasse mit einem angegebenen Passwort. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Der Dateityp, der sein Format angibt (z. B. docx, pdf, xlsx usw.). (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Die Formatfamilie des Dokuments, die seinen Typ angibt (z. B. Bild, Pdf, Tabellenkalkulation usw.). (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Das Passwort zum Öffnen eines verschlüsselten Dokuments. (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetloadoptions/default/) | Ruft den Standardwert für die Klasse ab. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
    # Wasserzeichen-Operationen hier ausführen
    pass
```

### Siehe auch
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
