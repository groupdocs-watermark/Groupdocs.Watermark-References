---
title: "Classe ImageWatermark"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta una filigrana immagine."
type: docs
url: /it/python-net/groupdocs.watermark.watermarks/imagewatermark/
is_root: false
weight: 40
---


## ImageWatermark class

Rappresenta una filigrana immagine.

Per saperne di più:
- Adding image watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks

Il tipo ImageWatermark espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#file_path) | Inizializza una nuova istanza di ImageWatermark con un percorso file specificato. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#stream) | Inizializza un nuovo ImageWatermark con lo stream immagine fornito. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/dispose/) | Elimina l'istanza corrente. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | La proprietà che indica se le dimensioni e le coordinate della filigrana sono calcolate considerando i margini del genitore. Se impostata su True, i calcoli considerano i margini del genitore; per impostazione predefinita il valore è False e i margini del genitore sono ignorati. (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | L'altezza desiderata di questo [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | L'allineamento orizzontale di questa Watermark. (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | La proprietà che indica se la filigrana deve essere posizionata sullo sfondo. Se true, la filigrana è posizionata in basso; altrimenti, è posizionata in alto (il valore predefinito è False). (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | Le impostazioni di margine di questa Watermark. (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | L'opacità di questo [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | Le impostazioni di configurazione delle pagine di questo Watermark. (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | L'angolo di rotazione di questo [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) in gradi. (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | La proprietà indica se salvare le informazioni sui watermark aggiunti nei metadati del documento. (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | Il fattore di scala di questo [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/), che definisce come la dimensione del watermark dipende dalla dimensione del genitore. (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | Il tipo di dimensionamento del watermark. (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | Le opzioni per definire un watermark ripetuto. (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | L'allineamento verticale di questo [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | La larghezza desiderata di questo [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | La coordinata x di questo [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | La coordinata y di questo [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (eredita da [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |

### Esempio

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

def add_image_watermark_from_stream():
    # Carica i dati dell'immagine in uno stream
    with open("./logo.png", "rb") as f:
        image_data = f.read()

    # Apri il documento e aggiungi il watermark immagine
    with Watermarker("./sample.docx") as watermarker:
        with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
            watermarker.add(watermark)
        watermarker.save("./output.docx")
```

### Guides
Guide operative che utilizzano `ImageWatermark`:

* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)

### Vedi anche
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
