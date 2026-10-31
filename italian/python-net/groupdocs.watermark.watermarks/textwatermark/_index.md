---
title: "Classe TextWatermark"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta una filigrana di testo."
type: docs
url: /it/python-net/groupdocs.watermark.watermarks/textwatermark/
is_root: false
weight: 110
---


## TextWatermark class

Rappresenta una filigrana di testo.

Per saperne di più:
- Adding text watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks

Il tipo TextWatermark espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/#text-font) | Inizializza una nuova TextWatermark con il testo e il font specificati. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [background_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/background_color/) | Il colore di sfondo del testo. |
| [font](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/font/) | Il carattere del testo. |
| [foreground_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/foreground_color/) | Il colore di primo piano del testo. |
| [padding](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/padding/) | Le impostazioni di padding di questa TextWatermark, applicabili solo ai file immagine. |
| [text](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text/) | Il testo da utilizzare come filigrana. |
| [text_alignment](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text_alignment/) | L'allineamento del testo della filigrana. |
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
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Guides
Guide operative che utilizzano `TextWatermark`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Vedi anche
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
