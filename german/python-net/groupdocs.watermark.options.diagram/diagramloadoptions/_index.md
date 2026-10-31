---
title: "DiagramLoadOptions Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt Ladevorgangsoptionen für ein Visio-Dokument dar."
type: docs
url: /de/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/
is_root: false
weight: 10
---


## DiagramLoadOptions class

Stellt Ladevorgangsoptionen für ein Visio-Dokument dar.

Der DiagramLoadOptions-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/) | Initialisiert eine neue Instanz der Klasse [`DiagramLoadOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/#password) | Initialisiert eine neue Instanz der Klasse [`DiagramLoadOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/) mit einem angegebenen Passwort. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Der Dateityp, der sein Format angibt (z. B. docx, pdf, xlsx usw.). (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Die Formatfamilie des Dokuments, die seinen Typ angibt (z. B. Bild, Pdf, Tabellenkalkulation usw.). (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Das Passwort zum Öffnen eines verschlüsselten Dokuments. (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/default/) | Ruft den Standardwert für die Klasse ab. |

### Beispiel

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.diagram import DiagramLoadOptions
import groupdocs.watermark.contents.diagram as gwc_vsdx

load_options = DiagramLoadOptions()
with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
    content = watermarker.get_content()
    # Formen hier manipulieren
    watermarker.save("output.vsdx")
```

### Siehe auch
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
