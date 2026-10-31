---
title: "PresentationLoadOptions Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt Ladeoptionen für ein Presentation-Dokument dar."
type: docs
url: /de/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/
is_root: false
weight: 30
---


## PresentationLoadOptions class

Stellt Ladeoptionen für ein Presentation-Dokument dar.

Der Typ PresentationLoadOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/) | Initialisiert eine neue Instanz der [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) Klasse. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/#password) | Initialisiert eine neue Instanz der PresentationLoadOptions Klasse mit einem angegebenen Passwort. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Der Dateityp, der sein Format angibt (z. B. docx, pdf, xlsx usw.). (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Die Formatfamilie des Dokuments, die seinen Typ angibt (z. B. Bild, Pdf, Tabellenkalkulation usw.). (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Das Passwort zum Öffnen eines verschlüsselten Dokuments. (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/default/) | Ruft den Standardwert für die Klasse ab. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
    # mit dem Dokument arbeiten
    pass
```

### Siehe auch
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
