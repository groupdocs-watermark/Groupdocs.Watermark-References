---
title: "Klasse PreviewOptions"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung."
type: docs
url: /de/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung.

Der Typ PreviewOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | Initialisiert eine neue PreviewOptions-Instanz, die den Ausgabestream nach Gebrauch schließt. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | Initialisiert eine neue PreviewOptions-Instanz, die den Ausgabestream an den Client zurückgibt für weitere Verwendung. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | Der Delegat zur Erstellung des Seitenstreams, der verwendet wird, um für jede gerenderte Seite einen beschreibbaren Stream zu erhalten. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | Die Höhe der Seitenvorschau. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | Das Array von Seitenzahlen, für die Vorschauen erzeugt werden sollen. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | Das Bildformat der Vorschau. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | Der Delegat für den Abschluss der Seitenvorschau. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | Die Breite der Seitenvorschau. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Stellen Sie für jede zu rendernde Seite einen beschreibbaren Dateistream bereit
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### Guides
Aufgabenleitfäden, die `PreviewOptions` verwenden:

* [Document preview](/watermark/python-net/guides/preview/)

### Siehe auch
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
