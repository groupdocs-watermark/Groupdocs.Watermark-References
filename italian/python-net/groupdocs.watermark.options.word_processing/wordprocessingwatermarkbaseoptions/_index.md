---
title: "classe WordProcessingWatermarkBaseOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta la classe base per le opzioni di aggiunta della filigrana a un documento Word."
type: docs
url: /it/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/
is_root: false
weight: 90
---


## WordProcessingWatermarkBaseOptions class

Rappresenta la classe base per le opzioni di aggiunta della filigrana a un documento Word.

Il tipo WordProcessingWatermarkBaseOptions espone i seguenti membri:

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | Il testo descrittivo (alternativo) che sarà associato a una forma. |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | Gli effetti da applicare al watermark, specificati come un'istanza di [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) o di [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/). |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | La proprietà indica se la modifica della forma in Word è vietata. |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | Il tipo di blocco del watermark. |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | Il nome della forma. |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | La password utilizzata per bloccare il watermark. |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Ottiene il valore predefinito per la classe. (ereditato da [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Esempio

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

### Vedi anche
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
