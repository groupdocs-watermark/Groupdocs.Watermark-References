---
title: "DiagramContent-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar ett Visio‑dokument."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.diagram/diagramcontent/
is_root: false
weight: 10
---


## DiagramContent class

Representerar ett Visio‑dokument.

Läs mer:
- Add watermarks to diagram documents https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents
- Existing objects in diagram document https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+diagram+document

DiagramContent-typen visar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Avslutar den aktuella instansen. (ärvd från [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Hittar bilder enligt de angivna sökkriterierna. Söket utförs i de objekt som anges i [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Hittar möjliga vattenmärken enligt de angivna sökkriterierna. Söket utförs på de objekt som listas i [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (ärvd från [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [header_footer](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/header_footer/) | Rubriken och sidfoten för detta DiagramContent. |
| [pages](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/pages/) | Samlingen av alla sidor för detta [`DiagramContent`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/). |

### Exempel

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.diagram import DiagramLoadOptions
import groupdocs.watermark.contents.diagram as gwc_vsdx

load_options = DiagramLoadOptions()
with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
    content = watermarker.get_content()
    for shape in content.pages[0].shapes:
        if shape.text and "© Aspose 2016" in shape.text:
            shape.text = "© GroupDocs 2017"
    watermarker.save("output.vsdx")
```

### Se även
* module [`groupdocs.watermark.contents.diagram`](/watermark/python-net/groupdocs.watermark.contents.diagram/)
