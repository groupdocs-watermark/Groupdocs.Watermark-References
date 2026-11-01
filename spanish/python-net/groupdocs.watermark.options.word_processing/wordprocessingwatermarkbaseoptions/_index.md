---
title: "Clase WordProcessingWatermarkBaseOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa la clase base para las opciones de agregar marcas de agua a un documento Word."
type: docs
url: /es/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/
is_root: false
weight: 90
---


## WordProcessingWatermarkBaseOptions class

Representa la clase base para las opciones de agregar marcas de agua a un documento Word.

El tipo WordProcessingWatermarkBaseOptions expone los siguientes miembros:

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | El texto descriptivo (alternativo) que se asociará a una forma. |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | Los efectos a aplicar a la marca de agua, especificados como una instancia de [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) o [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/). |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | La propiedad indica si la edición de la forma en Word está prohibida. |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | El tipo de bloqueo de la marca de agua. |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | El nombre de la forma. |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | La contraseña utilizada para bloquear la marca de agua. |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtiene el valor predeterminado para la clase. (heredado de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Ejemplo

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

### Ver también
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
