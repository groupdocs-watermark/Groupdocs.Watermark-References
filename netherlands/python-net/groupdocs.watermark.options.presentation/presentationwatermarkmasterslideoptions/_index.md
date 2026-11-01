---
title: "PresentationWatermarkMasterSlideOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Geeft opties weer bij het toevoegen van een watermerk aan een master‑dia van een Presentatie‑document."
type: docs
url: /nl/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/
is_root: false
weight: 110
---


## PresentationWatermarkMasterSlideOptions class

Geeft opties weer bij het toevoegen van een watermerk aan een master‑dia van een Presentatie‑document.

Meer informatie:
- [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

Zie de gebruiksvoorbeelden in [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/).

Het PresentationWatermarkMasterSlideOptions type toont de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/__init__/) | Initialiseert een nieuw exemplaar van de [`PresentationWatermarkMasterSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [master_slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/master_slide_index/) | De index van de master slide waaraan het watermerk moet worden toegevoegd. |
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

watermarker = gw.Watermarker("presentation.pptx")
watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))

master_opts = gwo_ppt.PresentationWatermarkMasterSlideOptions()
master_opts.master_slide_index = -1
watermarker.add(watermark, master_opts)
```

### Zie ook
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
