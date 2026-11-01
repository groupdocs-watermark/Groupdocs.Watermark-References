---
title: "WordProcessingImageEffects klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt effecten voor die op een afbeeldingwatermerk voor een Word-document kunnen worden toegepast."
type: docs
url: /nl/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/
is_root: false
weight: 30
---


## WordProcessingImageEffects class

Stelt effecten voor die op een afbeeldingwatermerk voor een Word-document kunnen worden toegepast.

Het WordProcessingImageEffects type bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/) | Initialiseert een nieuw exemplaar van de [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | De lijnopmaakinstellingen voor de afbeeldingsrand. (geërfd van [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | De helderheid van de afbeelding. Moet een float zijn tussen 0.0 (donkerst) en 1.0 (helderst). De standaardwaarde is 0.5. (geërfd van [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | De kleurwaarde van de afbeelding die als transparant wordt behandeld. De standaardwaarde is een volledig transparante kleur. (geërfd van [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | Het contrast voor de opgegeven afbeelding. Moet een float zijn tussen 0.0 (minst contrast) en 1.0 (meest contrast). De standaardwaarde is 0.5. (geërfd van [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | De eigenschap geeft aan of een afbeelding in grijstintenmodus wordt weergegeven. (geërfd van [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark, Color
from groupdocs.watermark.options.word_processing import (
    WordProcessingLoadOptions, WordProcessingWatermarkSectionOptions, WordProcessingImageEffects,
)

def add_watermark_with_effects():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        with ImageWatermark("./logo.png") as watermark:
            effects = WordProcessingImageEffects()
            effects.brightness = 0.7
            effects.contrast = 0.6
            effects.chroma_key = Color.red

            options = WordProcessingWatermarkSectionOptions()
            options.name = "Shape 1"
            options.alternative_text = "Company logo watermark"
            options.effects = effects
            watermarker.add(watermark, options)

        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_watermark_with_effects()
```

### Zie ook
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
