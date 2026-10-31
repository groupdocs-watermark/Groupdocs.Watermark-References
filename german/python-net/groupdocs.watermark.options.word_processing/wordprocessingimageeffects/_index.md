---
title: "Klasse WordProcessingImageEffects"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt Effekte dar, die auf ein Bildwasserzeichen für ein Word-Dokument angewendet werden können."
type: docs
url: /de/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/
is_root: false
weight: 30
---


## WordProcessingImageEffects class

Stellt Effekte dar, die auf ein Bildwasserzeichen für ein Word-Dokument angewendet werden können.

Der Typ WordProcessingImageEffects stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/) | Initialisiert eine neue Instanz der Klasse [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/). |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | Die Einstellungen für das Linienformat des Bildrandes. (geerbt von [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | Die Helligkeit des Bildes. Muss ein Fließkommawert zwischen 0.0 (dunkelste) und 1.0 (hellste) sein. Der Standardwert ist 0.5. (geerbt von [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | Der Farbwert des Bildes, der als transparent behandelt wird. Der Standardwert ist eine vollständig transparente Farbe. (geerbt von [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | Der Kontrast für das angegebene Bild. Muss ein Float zwischen 0.0 (geringster Kontrast) und 1.0 (höchster Kontrast) sein. Der Standardwert ist 0.5. (geerbt von [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | Die Eigenschaft gibt an, ob ein Bild im Graustufenmodus angezeigt wird. (geerbt von [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |

### Beispiel

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

### Siehe auch
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
