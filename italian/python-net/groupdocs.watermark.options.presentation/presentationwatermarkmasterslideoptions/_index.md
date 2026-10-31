---
title: "Classe PresentationWatermarkMasterSlideOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta le opzioni quando si aggiunge una filigrana a una diapositiva master di un documento Presentation."
type: docs
url: /it/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/
is_root: false
weight: 110
---


## PresentationWatermarkMasterSlideOptions class

Rappresenta le opzioni quando si aggiunge una filigrana a una diapositiva master di un documento Presentation.

Per saperne di più:
- [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

Vedi gli esempi d'uso in [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/).

Il tipo PresentationWatermarkMasterSlideOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/__init__/) | Inizializza una nuova istanza della classe [`PresentationWatermarkMasterSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [master_slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/master_slide_index/) | L'indice della diapositiva master a cui aggiungere la filigrana. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | Il testo descrittivo (alternativo) che sarà associato a una forma. (eredita da [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | Gli effetti da applicare al watermark, specificati come un'istanza di [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) o [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/). (eredita da [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | La proprietà indica se la modifica della forma in PowerPoint è vietata. (eredita da [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | Il nome della forma. (eredita da [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | La proprietà che indica se i caratteri del watermark di testo sono mescolati con caratteri illeggibili. (eredita da [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Ottiene il valore predefinito per la classe. (ereditato da [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Esempio

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.presentation as gwo_ppt

watermarker = gw.Watermarker("presentation.pptx")
watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))

master_opts = gwo_ppt.PresentationWatermarkMasterSlideOptions()
master_opts.master_slide_index = -1
watermarker.add(watermark, master_opts)
```

### Vedi anche
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
