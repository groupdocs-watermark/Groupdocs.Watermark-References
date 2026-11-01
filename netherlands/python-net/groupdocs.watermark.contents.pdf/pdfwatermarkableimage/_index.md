---
title: "PdfWatermarkableImage klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt een afbeelding binnen een Pdf-document voor."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/
is_root: false
weight: 240
---


## PdfWatermarkableImage class

Stelt een afbeelding binnen een Pdf-document voor.

Het PdfWatermarkableImage type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/#image_data) | Initialiseert een nieuw exemplaar van de [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) klasse met gespecificeerde afbeeldingsgegevens. |

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
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### Zie ook
* module [`groupdocs.watermark.contents.pdf`](/watermark/python-net/groupdocs.watermark.contents.pdf/)
