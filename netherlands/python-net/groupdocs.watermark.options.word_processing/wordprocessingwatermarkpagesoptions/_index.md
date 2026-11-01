---
title: "WordProcessingWatermarkPagesOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt opties voor bij het toevoegen van een watermerk aan Word-documentpagina's voor."
type: docs
url: /nl/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/
is_root: false
weight: 110
---


## WordProcessingWatermarkPagesOptions class

Stelt opties voor bij het toevoegen van een watermerk aan Word-documentpagina's voor.

Meer informatie:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents

Het WordProcessingWatermarkPagesOptions type bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/) | Initialiseert een nieuw exemplaar van de WordProcessingWatermarkPagesOptions klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/page_numbers/) | De paginanummers om het watermerk toe te voegen. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | De beschrijvende (alternatieve) tekst die aan een vorm wordt gekoppeld. (geërfd van [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | De effecten die op het watermerk moeten worden toegepast, gespecificeerd als een [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) of [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/) instantie. (geërfd van [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | De eigenschap geeft aan of bewerken van de vorm in Word verboden is. (geërfd van [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | Het type vergrendeling van het watermerk. (geërfd van [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | De naam van de vorm. (geërfd van [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | Het wachtwoord dat wordt gebruikt om het watermerk te vergrendelen. (geërfd van [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Haalt de standaardwaarde op voor de klasse. (geërfd van [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions, WordProcessingWatermarkPagesOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = WordProcessingLoadOptions()
with Watermarker(r"D:\test.doc", load_options) as watermarker:
    watermark = TextWatermark("text", Font("Arial", 42))
    options = WordProcessingWatermarkPagesOptions()
    options.page_numbers = [1]

    watermarker.add(watermark, options)
    watermarker.save()
```

### Zie ook
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
