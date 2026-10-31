---
title: "Classe PdfArtifactWatermarkOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta le opzioni di aggiunta di filigrana quando si aggiunge una filigrana di artefatto a un documento PDF."
type: docs
url: /it/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
is_root: false
weight: 20
---


## PdfArtifactWatermarkOptions class

Rappresenta le opzioni di aggiunta di filigrana quando si aggiunge una filigrana di artefatto a un documento PDF.

Per saperne di più:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

Il tipo PdfArtifactWatermarkOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/__init__/) | Inizializza una nuova istanza della classe [`PdfArtifactWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/page_index/) | L'indice della pagina a cui aggiungere la filigrana. |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Ottiene il valore predefinito per la classe. (ereditato da [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfArtifactWatermarkOptions

with Watermarker("./test.pdf", PdfLoadOptions()) as watermarker:
    with ImageWatermark("./icon.png") as watermark:
        watermark.horizontal_alignment = HorizontalAlignment.RIGHT
        watermark.vertical_alignment = VerticalAlignment.BOTTOM
        options = PdfArtifactWatermarkOptions()
        options.page_index = -1  # default: all pages
        watermarker.add(watermark, options)
        watermarker.save()
```

### Vedi anche
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
