---
title: "Classe WordProcessingWatermarkSectionOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta le opzioni quando si aggiunge una filigrana forma a una sezione di documento Word."
type: docs
url: /it/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/
is_root: false
weight: 120
---


## WordProcessingWatermarkSectionOptions class

Rappresenta le opzioni quando si aggiunge una filigrana forma a una sezione di documento Word.

Per saperne di più:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents

Il tipo WordProcessingWatermarkSectionOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/__init__/) | Inizializza una nuova istanza della classe [`WordProcessingWatermarkSectionOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [section_index](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/section_index/) | L'indice della sezione a cui aggiungere la filigrana. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | Il testo descrittivo (alternativo) che sarà associato a una forma. (eredita da [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | Gli effetti da applicare alla filigrana, specificati come un'istanza di [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) o di [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/). (eredita da [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | La proprietà indica se la modifica della forma in Word è vietata. (eredita da [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | Il tipo di blocco della filigrana. (eredita da [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | Il nome della forma. (eredita da [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | La password utilizzata per bloccare la filigrana. (eredita da [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Ottiene il valore predefinito per la classe. (ereditato da [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.word_processing import (
    WordProcessingLoadOptions, WordProcessingWatermarkSectionOptions,
)

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36.0))
    watermark.horizontal_alignment = HorizontalAlignment.CENTER
    watermark.vertical_alignment = VerticalAlignment.CENTER
    watermark.foreground_color = Color.red

    options = WordProcessingWatermarkSectionOptions()
    options.section_index = 0

    watermarker.add(watermark, options)
    watermarker.save("./output.docx")
```

### Vedi anche
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
