---
title: "Clase PresentationWatermarkMasterHandoutSlideOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa las opciones al agregar una marca de agua a una diapositiva maestra de folleto de documento Presentation."
type: docs
url: /es/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterhandoutslideoptions/
is_root: false
weight: 90
---


## PresentationWatermarkMasterHandoutSlideOptions class

Representa las opciones al agregar una marca de agua a una diapositiva maestra de folleto de documento Presentation.

Aprende más:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

Vea los ejemplos de uso en [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/).

El tipo PresentationWatermarkMasterHandoutSlideOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterhandoutslideoptions/__init__/) | Inicializa una nueva instancia de la clase [`PresentationWatermarkMasterHandoutSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterhandoutslideoptions/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | El texto descriptivo (alternativo) que se asociará a una forma. (heredado de [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | Los efectos a aplicar a la marca de agua, especificados como una instancia de [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) o [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/) . (heredado de [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | La propiedad indica si la edición de la forma en PowerPoint está prohibida. (heredado de [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | El nombre de la forma. (heredado de [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | La propiedad indica si los caracteres de la marca de agua de texto se mezclan con caracteres ilegibles. (heredado de [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtiene el valor predeterminado para la clase. (heredado de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Ejemplo

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.presentation as gwo_ppt
import groupdocs.watermark.contents.presentation as gwc_ppt

load_options = gwo_ppt.PresentationLoadOptions()
with gw.Watermarker("presentation.pptx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))
    handout_opts = gwo_ppt.PresentationWatermarkMasterHandoutSlideOptions()
    watermarker.add(watermark, handout_opts)
```

### Ver también
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
