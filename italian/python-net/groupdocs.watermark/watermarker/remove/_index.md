---
title: "metodo remove"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rimuove una filigrana dal documento."
type: docs
url: /it/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

Rimuove una filigrana dal documento.

Maggiori informazioni sulla rimozione delle filigrane: Rimozione delle filigrane trovate.

```python
def remove(self, possible_watermark):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | La filigrana da rimuovere. |

### Esempio

```python
from groupdocs.watermark import Watermarker

def remove_first_watermark():
    with Watermarker("./document.pdf") as watermarker:
        watermarks = watermarker.search()
        if watermarks:
            watermarker.remove(watermarks[0])
        watermarker.save("./output.pdf")
```

## remove {#possible_watermarks}

Rimuove tutte le filigrane nella collezione dal documento.

Maggiori informazioni sulla rimozione delle filigrane nella documentazione di GroupDocs.

```python
def remove(self, possible_watermarks):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | La raccolta di filigrane da rimuovere. |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # Rimuovi in ordine inverso per mantenere gli indici validi
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### Vedi anche
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
