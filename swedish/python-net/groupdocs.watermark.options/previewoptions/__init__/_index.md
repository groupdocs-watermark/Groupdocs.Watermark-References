---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny PreviewOptions-instans som stänger utdataflödet efter användning."
type: docs
url: /sv/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initierar en ny PreviewOptions-instans som stänger utdataflödet efter användning.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – Skapar en ström för en specifik sidoförhandsgranskning. |

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Tillhandahåll ett skrivbart filflöde för varje sida som ska renderas
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

Initierar en ny PreviewOptions-instans som returnerar utdataflödet till klienten för vidare användning.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable som skapar en ström för en specifik sidoförhandsgranskning. Tar emot sidnumret (`int`) och bör returnera en skrivbar ström (`io.RawIOBase`). |
| release_page_stream | `ReleasePageStream` | Callable som anropas när generering av sidoförhandsgranskning är klar och tillhandahåller utdataströmmen. |

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Tillhandahåll ett skrivbart filflöde för varje sida som ska renderas
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

### Se även
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
