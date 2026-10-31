---
title: "metodo add"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Aggiunge una filigrana al documento caricato."
type: docs
url: /it/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

Aggiunge una filigrana al documento caricato.

Maggiori informazioni su come aggiungere filigrane nella documentazione di GroupDocs.

```python
def add(self, watermark):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| watermark | `Watermark` | La filigrana da aggiungere al documento. |

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

## add {#watermark-options}

Aggiunge una filigrana al documento caricato utilizzando le opzioni di filigrana.

Maggiori informazioni su come aggiungere filigrane: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| watermark | `Watermark` | La filigrana da aggiungere al documento. |
| options | `WatermarkOptions` | Opzioni aggiuntive da usare quando si aggiunge la filigrana. |

**Returns:** None.

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

### Vedi anche
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
