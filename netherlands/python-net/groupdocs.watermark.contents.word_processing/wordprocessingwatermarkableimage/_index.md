---
title: "WordProcessingWatermarkableImage klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt een afbeelding binnen een Word-document voor."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/
is_root: false
weight: 190
---


## WordProcessingWatermarkableImage class

Stelt een afbeelding binnen een Word-document voor.

Het WordProcessingWatermarkableImage type exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/#image_data) | Initialiseert een nieuw exemplaar van de [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) klasse met opgegeven afbeeldingsgegevens. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/) | Voegt een watermerk toe aan deze [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). Deze methode gaat ervan uit dat watermerkverschuiving en -grootte in pixels worden gemeten (indien toegewezen). (geërfd van [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) | (geërfd van [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Zoekt afbeeldingen volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn gespecificeerd in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Haalt de afbeelding op als een byte‑array. (geërfd van [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd op de objecten die zijn vermeld in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | De hoogte van deze [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) in pixels. (geërfd van [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | De breedte van deze WatermarkableImage in pixels. (geërfd van [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |

### Voorbeeld

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()
image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### Zie ook
* module [`groupdocs.watermark.contents.word_processing`](/watermark/python-net/groupdocs.watermark.contents.word_processing/)
