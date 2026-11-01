---
title: "PreviewOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Biedt opties om vereisten en streamdelegaten in te stellen voor het genereren van een voorbeeld."
type: docs
url: /nl/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

Biedt opties om vereisten en streamdelegaten in te stellen voor het genereren van een voorbeeld.

Het type PreviewOptions exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | Initialiseert een nieuw PreviewOptions‑object dat de uitvoerstroom na gebruik sluit. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | Initialiseert een nieuw PreviewOptions‑object dat de uitvoerstroom teruggeeft aan de client voor verder gebruik. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | De delegate voor het maken van paginastromen die wordt gebruikt om een beschrijfbare stroom voor elke gerenderde pagina te verkrijgen. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | De hoogte van de paginavoorvertoning. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | De array met paginanummers waarvoor voorvertoningen moeten worden gegenereerd. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | Het formaat van de voorvertoningsafbeelding. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | De delegate voor het voltooien van de paginavoorvertoning. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | De breedte van de paginavoorvertoning. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Voorzie een schrijfbare bestandsstroom voor elke te renderen pagina.
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
Taakgidsen die `PreviewOptions` gebruiken:

* [Document preview](/watermark/python-net/guides/preview/)

### Zie ook
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
