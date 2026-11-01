---
title: "Clase WordProcessingWatermarkPagesOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa las opciones al agregar una marca de agua a las páginas del documento Word."
type: docs
url: /es/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/
is_root: false
weight: 110
---


## WordProcessingWatermarkPagesOptions class

Representa las opciones al agregar una marca de agua a las páginas del documento Word.

Aprende más:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents

El tipo WordProcessingWatermarkPagesOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/) | Inicializa una nueva instancia de la clase WordProcessingWatermarkPagesOptions. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/page_numbers/) | Los números de página donde se añadirá la marca de agua. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | El texto descriptivo (alternativo) que se asociará a una forma. (heredado de [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | Los efectos a aplicar a la marca de agua, especificados como una instancia de [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) o [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/). (heredado de [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | La propiedad indica si la edición de la forma en Word está prohibida. (heredado de [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | El tipo de bloqueo de la marca de agua. (heredado de [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | El nombre de la forma. (heredado de [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | La contraseña utilizada para bloquear la marca de agua. (heredado de [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtiene el valor predeterminado para la clase. (heredado de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Ejemplo

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

### Ver también
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
