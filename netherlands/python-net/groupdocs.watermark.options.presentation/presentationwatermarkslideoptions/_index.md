---
title: "PresentationWatermarkSlideOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Geeft opties weer bij het toevoegen van een watermerk aan een dia van een Presentatie‑document."
type: docs
url: /nl/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/
is_root: false
weight: 140
---


## PresentationWatermarkSlideOptions class

Geeft opties weer bij het toevoegen van een watermerk aan een dia van een Presentatie‑document.

Meer informatie:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

Het type PresentationWatermarkSlideOptions bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/__init__/) | Initialiseert een nieuw exemplaar van de [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/slide_index/) | De index van de dia waarop het watermerk moet worden toegevoegd. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | De beschrijvende (alternatieve) tekst die aan een vorm wordt gekoppeld. (geërfd van [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | De effecten die op het watermerk moeten worden toegepast, gespecificeerd als een [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) of een [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/) instantie. (geërfd van [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | De eigenschap geeft aan of bewerken van de vorm in PowerPoint verboden is. (geërfd van [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | De naam van de vorm. (geërfd van [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | De eigenschap die aangeeft of de tekens van het tekstwatermerk gemengd zijn met onleesbare tekens. (geërfd van [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Haalt de standaardwaarde op voor de klasse. (geërfd van [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.presentation import (
    PresentationLoadOptions, PresentationWatermarkSlideOptions,
)

def add_watermark_to_slide():
    with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = PresentationWatermarkSlideOptions()
        options.slide_index = 0
        watermarker.add(watermark, options)

        watermarker.save("./output.pptx")
```

### Zie ook
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
