---
title: "Clase PresentationWatermarkBaseSlideOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Clase base para las opciones de agregar marcas de agua a un documento Presentation."
type: docs
url: /es/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
is_root: false
weight: 70
---


## PresentationWatermarkBaseSlideOptions class

Clase base para las opciones de agregar marcas de agua a un documento Presentation.

Aprende más:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

El tipo PresentationWatermarkBaseSlideOptions expone los siguientes miembros:

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | El texto descriptivo (alternativo) que se asociará a una forma. |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | Los efectos a aplicar a la marca de agua, especificados como una instancia de [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) o [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/). |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | La propiedad indica si la edición de la forma en PowerPoint está prohibida. |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | El nombre de la forma. |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | La propiedad que indica si los caracteres de la marca de agua de texto se mezclan con caracteres ilegibles. |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtiene el valor predeterminado para la clase. (heredado de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationWatermarkMasterSlideOptions
from groupdocs.watermark.options.presentation import PresentationWatermarkLayoutSlideOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./presentation.pptx") as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 8.0))

    master_options = PresentationWatermarkMasterSlideOptions()
    master_options.master_slide_index = 0
    watermarker.add(watermark, master_options)

    layout_options = PresentationWatermarkLayoutSlideOptions()
    layout_options.layout_slide_index = 0
    watermarker.add(watermark, layout_options)

    watermarker.save("./output.pptx")
```

### Ver también
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
