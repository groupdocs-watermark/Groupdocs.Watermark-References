---
title: "EmailLoadOptions Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt die Dokument-Ladeoptionen für eine E-Mail-Nachricht dar."
type: docs
url: /de/python-net/groupdocs.watermark.options.email/emailloadoptions/
is_root: false
weight: 10
---


## EmailLoadOptions class

Stellt die Dokument-Ladeoptionen für eine E-Mail-Nachricht dar.

Der Typ EmailLoadOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/) | Initialisiert eine neue Instanz der [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/) Klasse. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Der Dateityp, der sein Format angibt (z. B. docx, pdf, xlsx usw.). (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Die Formatfamilie des Dokuments, die seinen Typ angibt (z. B. Bild, Pdf, Tabellenkalkulation usw.). (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Das Passwort zum Öffnen eines verschlüsselten Dokuments. (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/default/) | Ruft den Standardwert für die Klasse ab. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # Hier E-Mail-Inhalt manipulieren
    watermarker.save("./output.msg")
```

### Siehe auch
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
