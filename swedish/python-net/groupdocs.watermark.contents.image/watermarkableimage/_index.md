---
title: "WatermarkableImage klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar en bild i ett dokument."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.image/watermarkableimage/
is_root: false
weight: 90
---


## WatermarkableImage class

Representerar en bild i ett dokument.

Läs mer:
- https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document

Den WatermarkableImage-typen exponerar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/#watermark) | Lägger till ett vattenmärke till detta [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). Denna metod antar att vattenmärkesförskjutning och storlek mäts i pixlar (om de är tilldelade). |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) |  |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Hämtar bilden som en byte-array. |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Hittar bilder enligt de angivna sökkriterierna. Söket utförs i de objekt som anges i [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Hittar möjliga vattenmärken enligt de angivna sökkriterierna. Söket utförs på de objekt som listas i [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | Höjden på detta [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) i pixlar. |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | Bredden på detta WatermarkableImage i pixlar. |

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker(r"D:\input.doc") as watermarker:
    # Initiera textvattenmärke.
    watermark = TextWatermark("DRAFT", Font("Arial", 19))

    # Hitta alla bilder i dokumentet.
    images = watermarker.get_images()

    # Lägg till vattenmärke till varje bild.
    for img in images:
        img.add(watermark)

    # Spara ändringar.
    watermarker.save(r"D:\output.doc")
```

### Se även
* module [`groupdocs.watermark.contents.image`](/watermark/python-net/groupdocs.watermark.contents.image/)
