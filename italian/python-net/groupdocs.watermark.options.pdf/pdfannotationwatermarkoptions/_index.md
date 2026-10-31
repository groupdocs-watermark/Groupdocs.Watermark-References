---
title: "Classe PdfAnnotationWatermarkOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta le opzioni di aggiunta di filigrana quando si aggiunge una filigrana di annotazione a un documento PDF."
type: docs
url: /it/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
is_root: false
weight: 10
---


## PdfAnnotationWatermarkOptions class

Rappresenta le opzioni di aggiunta di filigrana quando si aggiunge una filigrana di annotazione a un documento PDF.

Per saperne di più:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

Il tipo PdfAnnotationWatermarkOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/__init__/) | Inizializza una nuova istanza della classe [`PdfAnnotationWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/page_index/) | L'indice della pagina a cui aggiungere la filigrana. |
| [print_only](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/print_only/) | Il valore che indica se l'annotazione verrà stampata ma non visualizzata in un'applicazione di visualizzazione PDF. |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Ottiene il valore predefinito per la classe. (ereditato da [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfAnnotationWatermarkOptions

def add_annotation_image_watermark():
    load_options = PdfLoadOptions()
    with Watermarker("./test.pdf", load_options) as watermarker:
        with ImageWatermark("./icon.png") as watermark:
            options = PdfAnnotationWatermarkOptions()
            # PageIndex = -1 applica la filigrana a tutte le pagine (predefinito)
            watermarker.add(watermark, options)
        watermarker.save("./output.pdf")
```

### Vedi anche
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
