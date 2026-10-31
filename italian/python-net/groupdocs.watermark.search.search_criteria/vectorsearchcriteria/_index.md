---
title: "Classe VectorSearchCriteria"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta i criteri che consentono il filtraggio per colore del watermark."
type: docs
url: /it/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/
is_root: false
weight: 170
---


## VectorSearchCriteria class

Rappresenta i criteri che consentono il filtraggio per colore del watermark.

Per saperne di più:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Il tipo VectorSearchCriteria espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/__init__/) | Inizializza una nuova istanza di [`VectorSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/). |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Combina questo SearchCriteria con altri criteri usando l'operatore logico AND. (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Negare questo SearchCriteria. (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Combina questo SearchCriteria con altri criteri usando l'operatore logico OR. (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [vector_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/vector_color_range/) | L'intervallo di colori usato per filtrare i watermark vettoriali per colore di primo piano. |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import VectorSearchCriteria, ColorRange
from groupdocs.watermark.watermarks import Color

with Watermarker("./document.pdf") as watermarker:
    search_criteria = VectorSearchCriteria()
    watermark_color = Color.from_argb(255, 169, 170, 174)  # #a9aaae
    color_range = ColorRange(watermark_color)
    color_range.min_brightness = 0.1
    color_range.max_brightness = 0.7
    search_criteria.vector_color_range = color_range

    possible_watermarks = watermarker.search(search_criteria)
    possible_watermarks.clear()
    watermarker.save("./output.pdf")
```

### Vedi anche
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
