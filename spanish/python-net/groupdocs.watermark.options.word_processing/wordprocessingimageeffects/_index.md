---
title: "Clase WordProcessingImageEffects"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa los efectos que pueden aplicarse a una marca de agua de imagen para un documento Word."
type: docs
url: /es/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/
is_root: false
weight: 30
---


## WordProcessingImageEffects class

Representa los efectos que pueden aplicarse a una marca de agua de imagen para un documento Word.

El tipo WordProcessingImageEffects expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/) | Inicializa una nueva instancia de la clase [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | La configuración del formato de línea para el borde de la imagen. (heredado de [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | El brillo de la imagen. Debe ser un número de punto flotante entre 0.0 (más tenue) y 1.0 (más brillante). El valor predeterminado es 0.5. (heredado de [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | El valor de color de la imagen que se tratará como transparente. El valor predeterminado es un color totalmente transparente. (heredado de [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | El contraste de la imagen especificada. Debe ser un número de punto flotante entre 0.0 (menor contraste) y 1.0 (mayor contraste). El valor predeterminado es 0.5. (heredado de [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | La propiedad indica si una imagen se mostrará en modo escala de grises. (heredado de [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |

### Ejemplo

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

### Ver también
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
