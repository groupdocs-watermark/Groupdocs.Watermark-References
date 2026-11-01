---
title: "PresentationWatermarkLayoutSlideOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Geeft opties weer bij het toevoegen van een watermerk aan een lay-out‑dia van een Presentatie‑document."
type: docs
url: /nl/python-net/groupdocs.watermark.options.presentation/presentationwatermarklayoutslideoptions/
is_root: false
weight: 80
---


## PresentationWatermarkLayoutSlideOptions class

Geeft opties weer bij het toevoegen van een watermerk aan een lay-out‑dia van een Presentatie‑document.

Meer informatie:

- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

Zie de gebruiksvoorbeelden in [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/).

Het type PresentationWatermarkLayoutSlideOptions geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarklayoutslideoptions/__init__/) | Initialiseert een nieuw exemplaar van de [`PresentationWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkoptions/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [layout_slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarklayoutslideoptions/layout_slide_index/) | De index van de lay-outdia waarop het watermerk moet worden toegevoegd. |
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
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.presentation as gwo_ppt
import groupdocs.watermark.contents.presentation as gwc_ppt

load_options = gwo_ppt.PresentationLoadOptions()
with gw.Watermarker("presentation.pptx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))
    layout_opts = gwo_ppt.PresentationWatermarkLayoutSlideOptions()
    layout_opts.layout_slide_index = -1  # apply to all layout slides
    watermarker.add(watermark, layout_opts)
```

### Zie ook
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
