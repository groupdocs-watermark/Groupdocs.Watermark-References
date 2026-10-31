---
title: "Classe WordProcessingWatermarkPagesOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta le opzioni quando si aggiunge una filigrana alle pagine del documento Word."
type: docs
url: /it/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/
is_root: false
weight: 110
---


## WordProcessingWatermarkPagesOptions class

Rappresenta le opzioni quando si aggiunge una filigrana alle pagine del documento Word.

Per saperne di più:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents

Il tipo WordProcessingWatermarkPagesOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/) | Inizializza una nuova istanza della classe WordProcessingWatermarkPagesOptions. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/page_numbers/) | I numeri di pagina a cui aggiungere la filigrana. |
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

### Vedi anche
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
