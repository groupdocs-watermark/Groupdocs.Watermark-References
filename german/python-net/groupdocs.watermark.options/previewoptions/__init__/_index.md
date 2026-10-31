---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue PreviewOptions-Instanz, die den Ausgabestream nach Gebrauch schließt."
type: docs
url: /de/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialisiert eine neue PreviewOptions-Instanz, die den Ausgabestream nach Gebrauch schließt.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – Erstellt einen Stream für eine bestimmte Seitenvorschau. |

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

## __init__ {#create_page_stream-release_page_stream}

Initialisiert eine neue PreviewOptions-Instanz, die den Ausgabestream an den Client zurückgibt für weitere Verwendung.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable, das einen Stream für eine bestimmte Seitenvorschau erstellt. Empfängt die Seitennummer (`int`) und sollte einen beschreibbaren Stream (`io.RawIOBase`) zurückgeben. |
| release_page_stream | `ReleasePageStream` | Callable, das aufgerufen wird, wenn die Generierung der Seitenvorschau abgeschlossen ist und den Ausgabestream bereitstellt. |

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

### Siehe auch
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
