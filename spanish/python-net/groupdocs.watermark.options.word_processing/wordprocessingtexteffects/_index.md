---
title: "Clase WordProcessingTextEffects"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa los efectos que pueden aplicarse a una marca de agua de texto para un documento Word."
type: docs
url: /es/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/
is_root: false
weight: 80
---


## WordProcessingTextEffects class

Representa los efectos que pueden aplicarse a una marca de agua de texto para un documento Word.

El tipo WordProcessingTextEffects expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/__init__/) | Inicializa una nueva instancia de la clase [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [flip_orientation](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/flip_orientation/) | La orientación de una forma. |
| [line_format](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/line_format/) | La configuración del formato de línea, representada por una instancia de [`OfficeLineFormat`](/watermark/python-net/groupdocs.watermark.contents/officelineformat/). (heredada de [`OfficeTextEffects`](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/default/) | Obtiene el valor predeterminado para la clase. |

### Ejemplo

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.word_processing as gwo_wp
import groupdocs.watermark.common as gwc
from groupdocs.watermark.contents import OfficeDashStyle, OfficeLineStyle

load_options = gwo_wp.WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 19.0))

    effects = gwo_wp.WordProcessingTextEffects()
    effects.line_format.enabled = True
    effects.line_format.color = gww.Color.red
    effects.line_format.dash_style = OfficeDashStyle.DASH_DOT_DOT
    effects.line_format.line_style = OfficeLineStyle.TRIPLE
    effects.line_format.weight = 1

    options = gwo_wp.WordProcessingWatermarkSectionOptions()
    options.effects = effects

    watermarker.add(watermark, options)
    watermarker.save("output.docx")
```

### Ver también
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
