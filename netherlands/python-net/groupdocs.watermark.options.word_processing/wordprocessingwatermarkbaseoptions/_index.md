---
title: "WordProcessingWatermarkBaseOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt de basisklasse voor watermerktoevoegopties aan een Word-document voor."
type: docs
url: /nl/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/
is_root: false
weight: 90
---


## WordProcessingWatermarkBaseOptions class

Stelt de basisklasse voor watermerktoevoegopties aan een Word-document voor.

Het WordProcessingWatermarkBaseOptions-type geeft de volgende leden weer:

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | De beschrijvende (alternatieve) tekst die aan een vorm wordt gekoppeld. |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | De effecten die op het watermerk moeten worden toegepast, gespecificeerd als een [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) of een [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/) instantie. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | De eigenschap geeft aan of bewerken van de vorm in Word verboden is. |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | Het watermerkvergrendeltype. |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | De naam van de vorm. |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | Het wachtwoord dat wordt gebruikt om het watermerk te vergrendelen. |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Haalt de standaardwaarde op voor de klasse. (geërfd van [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
from groupdocs.watermark.options.word_processing import WordProcessingWatermarkSectionOptions, WordProcessingLockType
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    watermark = TextWatermark("Protected", Font("Arial", 36.0))
    options = WordProcessingWatermarkSectionOptions()
    options.is_locked = True
    options.lock_type = WordProcessingLockType.ALLOW_ONLY_FORM_FIELDS
    watermarker.add(watermark, options)
    watermarker.save("./output.docx")
```

### Zie ook
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
