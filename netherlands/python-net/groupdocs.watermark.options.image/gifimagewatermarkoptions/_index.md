---
title: "GifImageWatermarkOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt opties voor het toevoegen van een watermark voor bij het toevoegen van een watermark aan een GIF-afbeelding voor."
type: docs
url: /nl/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
is_root: false
weight: 30
---


## GifImageWatermarkOptions class

Stelt opties voor het toevoegen van een watermark voor bij het toevoegen van een watermark aan een GIF-afbeelding voor.

Meer informatie:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

Het GifImageWatermarkOptions-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/__init__/) | Initialiseert een nieuw exemplaar van de [`GifImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/) klasse. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/__init__/#frame_index) | Initialiseert een nieuw exemplaar van de [`GifImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/) klasse met een opgegeven frame-index. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | De index van het frame om een watermerk toe te voegen. (geërfd van [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/)) |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Haalt de standaardwaarde op voor de klasse. (geërfd van [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.image import GifImageLoadOptions, GifImageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = GifImageLoadOptions()
with Watermarker(r"C:\test.gif", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 12))

    options = GifImageWatermarkOptions()
    options.frame_index = 0

    watermarker.add(watermark, options)
    watermarker.save()
```

### Zie ook
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
