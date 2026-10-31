---
title: "WordProcessingLoadOptions Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt Dokument-Ladeoptionen für ein Word-Dokument dar."
type: docs
url: /de/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/
is_root: false
weight: 40
---


## WordProcessingLoadOptions class

Stellt Dokument-Ladeoptionen für ein Word-Dokument dar.

Der Typ WordProcessingLoadOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/) | Initialisiert eine neue Instanz der [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) Klasse. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/#password) | Initialisiert eine neue Instanz der Klasse WordProcessingLoadOptions mit einem angegebenen Passwort. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Der Dateityp, der sein Format angibt (z. B. docx, pdf, xlsx usw.). (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Die Formatfamilie des Dokuments, die seinen Typ angibt (z. B. Bild, Pdf, Tabellenkalkulation usw.). (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Das Passwort zum Öffnen eines verschlüsselten Dokuments. (geerbt von [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/default/) | Ruft den Standardwert für die Klasse ab. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def process_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        # führt Operationen am Inhalt aus, z. B. schützen, ungeschützt lassen, Wasserzeichen hinzufügen
        watermarker.save("./output.docx")

if __name__ == "__main__":
    process_document()
```

### Siehe auch
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
