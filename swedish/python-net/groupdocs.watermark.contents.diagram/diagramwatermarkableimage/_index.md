---
title: "DiagramWatermarkableImage-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar en bild i ett Visio-dokument."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/
is_root: false
weight: 130
---


## DiagramWatermarkableImage class

Representerar en bild i ett Visio-dokument.

DiagramWatermarkableImage-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/#image_data) | Initierar en ny instans av [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) klassen med angivna bilddata. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/) | Lägger till ett vattenmärke till denna [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). Denna metod förutsätter att vattenmärkesförskjutning och storlek mäts i pixlar (om de har tilldelats). (ärvd från [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) | (ärvd från [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Hittar bilder enligt de angivna sökkriterierna. Söket utförs i de objekt som anges i [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Hämtar bilden som en bytearray. (ärvd från [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Hittar möjliga vattenmärken enligt de angivna sökkriterierna. Söket utförs på de objekt som listas i [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | Höjden på denna [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) i pixlar. (ärvd från [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | Bredden på detta WatermarkableImage i pixlar. (ärvd från [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |

### Exempel

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.diagram import DiagramLoadOptions
import groupdocs.watermark.contents.diagram as gwc_vsdx

load_options = DiagramLoadOptions()
with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
    content = watermarker.get_content()
    for shape in content.pages[0].shapes:
        if shape.image is not None:
            with open("test.png", "rb") as f:
                shape.image = gwc_vsdx.DiagramWatermarkableImage(f.read())
    watermarker.save("output.vsdx")
```

### Se även
* module [`groupdocs.watermark.contents.diagram`](/watermark/python-net/groupdocs.watermark.contents.diagram/)
