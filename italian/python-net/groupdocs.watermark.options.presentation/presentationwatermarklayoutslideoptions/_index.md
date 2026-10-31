---
title: "classe PresentationWatermarkLayoutSlideOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta le opzioni quando si aggiunge una filigrana a una diapositiva di layout di un documento Presentation."
type: docs
url: /it/python-net/groupdocs.watermark.options.presentation/presentationwatermarklayoutslideoptions/
is_root: false
weight: 80
---


## PresentationWatermarkLayoutSlideOptions class

Rappresenta le opzioni quando si aggiunge una filigrana a una diapositiva di layout di un documento Presentation.

Per saperne di più:

- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

Vedi gli esempi d'uso in [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/).

Il tipo PresentationWatermarkLayoutSlideOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarklayoutslideoptions/__init__/) | Inizializza una nuova istanza della classe [`PresentationWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkoptions/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [layout_slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarklayoutslideoptions/layout_slide_index/) | L'indice della diapositiva di layout a cui aggiungere la filigrana. |
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
import groupdocs.watermark.contents.presentation as gwc_ppt

load_options = gwo_ppt.PresentationLoadOptions()
with gw.Watermarker("presentation.pptx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))
    layout_opts = gwo_ppt.PresentationWatermarkLayoutSlideOptions()
    layout_opts.layout_slide_index = -1  # apply to all layout slides
    watermarker.add(watermark, layout_opts)
```

### Vedi anche
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
