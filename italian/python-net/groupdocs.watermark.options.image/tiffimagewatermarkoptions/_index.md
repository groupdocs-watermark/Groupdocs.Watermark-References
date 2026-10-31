---
title: "classe TiffImageWatermarkOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta le opzioni di aggiunta watermark quando si aggiunge un watermark a un'immagine TIFF."
type: docs
url: /it/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
is_root: false
weight: 100
---


## TiffImageWatermarkOptions class

Rappresenta le opzioni di aggiunta watermark quando si aggiunge un watermark a un'immagine TIFF.

Per saperne di più:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

Il tipo TiffImageWatermarkOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/__init__/) | Inizializza una nuova istanza della classe [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/__init__/#frame_index) | Inizializza una nuova istanza di [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/) con un indice di fotogramma specificato. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | L'indice del fotogramma a cui aggiungere una filigrana. (eredita da [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/)) |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Ottiene il valore predefinito per la classe. (ereditato da [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.image import TiffImageLoadOptions, TiffImageWatermarkOptions

with Watermarker("./image.tiff", TiffImageLoadOptions()) as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
    watermark.foreground_color = Color.red
    watermark.horizontal_alignment = HorizontalAlignment.CENTER
    watermark.vertical_alignment = VerticalAlignment.CENTER

    options = TiffImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)

    watermarker.save("./output.tiff")
```

### Vedi anche
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
