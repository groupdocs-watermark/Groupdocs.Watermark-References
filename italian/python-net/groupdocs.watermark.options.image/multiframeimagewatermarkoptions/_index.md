---
title: "classe MultiframeImageWatermarkOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta le opzioni di aggiunta watermark quando si aggiunge un watermark a un'immagine multi-frame."
type: docs
url: /it/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
is_root: false
weight: 70
---


## MultiframeImageWatermarkOptions class

Rappresenta le opzioni di aggiunta watermark quando si aggiunge un watermark a un'immagine multi-frame.

Per saperne di più: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

Il tipo MultiframeImageWatermarkOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/) | Inizializza una nuova istanza della classe [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/#frame_index) | Inizializza una nuova istanza della classe [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/) con un indice specificato del fotogramma. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | L'indice del fotogramma a cui aggiungere una filigrana. |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Ottiene il valore predefinito per la classe. (ereditato da [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.image import ImageLoadOptions, MultiframeImageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = ImageLoadOptions()
with Watermarker(r"C:\test.gif", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 12))
    options = MultiframeImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)
    watermarker.save()
```

### Vedi anche
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
