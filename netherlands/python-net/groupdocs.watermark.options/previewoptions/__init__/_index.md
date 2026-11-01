---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw PreviewOptions‑object dat de uitvoerstroom na gebruik sluit."
type: docs
url: /nl/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialiseert een nieuw PreviewOptions‑object dat de uitvoerstroom na gebruik sluit.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – Maakt een stream voor een specifieke paginavoorvertoning. |

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

## __init__ {#create_page_stream-release_page_stream}

Initialiseert een nieuw PreviewOptions‑object dat de uitvoerstroom teruggeeft aan de client voor verder gebruik.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable die een stream maakt voor een specifieke paginavoorvertoning. Ontvangt het paginanummer (`int`) en moet een beschrijfbare stream (`io.RawIOBase`) retourneren. |
| release_page_stream | `ReleasePageStream` | Callable die wordt aangeroepen wanneer de generatie van de paginavoorvertoning voltooid is en de uitvoerstroom levert. |

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

### Zie ook
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
