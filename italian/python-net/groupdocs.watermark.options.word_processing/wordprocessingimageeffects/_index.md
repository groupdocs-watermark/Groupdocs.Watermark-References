---
title: "Classe WordProcessingImageEffects"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta gli effetti che possono essere applicati a una filigrana immagine per un documento Word."
type: docs
url: /it/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/
is_root: false
weight: 30
---


## WordProcessingImageEffects class

Rappresenta gli effetti che possono essere applicati a una filigrana immagine per un documento Word.

Il tipo WordProcessingImageEffects espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/) | Inizializza una nuova istanza della classe [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | Le impostazioni del formato della linea per il bordo dell'immagine. (eredita da [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | La luminosità dell'immagine. Deve essere un valore float compreso tra 0.0 (più scuro) e 1.0 (più luminoso). Il valore predefinito è 0.5. (eredita da [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | Il valore di colore dell'immagine che sarà trattato come trasparente. Il valore predefinito è un colore completamente trasparente. (eredita da [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | Il contrasto per l'immagine specificata. Deve essere un valore float compreso tra 0.0 (meno contrasto) e 1.0 (massimo contrasto). Il valore predefinito è 0.5. (eredita da [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | La proprietà indica se un'immagine verrà visualizzata in modalità scala di grigi. (eredita da [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |

### Esempio

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

### Vedi anche
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
