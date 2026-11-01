---
title: "PreviewOptions-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Tillhandahåller alternativ för att ange krav och strömdelegeringar för förhandsgranskning."
type: docs
url: /sv/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

Tillhandahåller alternativ för att ange krav och strömdelegeringar för förhandsgranskning.

PreviewOptions-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | Initierar en ny PreviewOptions-instans som stänger utdataflödet efter användning. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | Initierar en ny PreviewOptions-instans som returnerar utdataflödet till klienten för vidare användning. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | Delegaten för skapande av sidström som används för att erhålla ett skrivbart flöde för varje renderad sida. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | Sidans förhandsgranskningshöjd. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | Arrayen med sidnummer för att generera förhandsgranskningar. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | Förhandsgranskningsbildformatet. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | Delegaten för slutförande av sidans förhandsgranskning. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | Sidans förhandsgranskningsbredd. |

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

### Guides
Uppgiftsguider som använder `PreviewOptions`:

* [Document preview](/watermark/python-net/guides/preview/)

### Se även
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
