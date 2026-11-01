---
title: "VectorSearchCriteria klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt criteria voor die filteren op watermerk kleur."
type: docs
url: /nl/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/
is_root: false
weight: 170
---


## VectorSearchCriteria class

Stelt criteria voor die filteren op watermerk kleur.

Meer informatie:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Het type VectorSearchCriteria bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/__init__/) | Initialiseert een nieuw [`VectorSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/) exemplaar. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Combineert dit SearchCriteria met andere criteria met behulp van de logische EN-operator. (geërfd van [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (geërfd van [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Negereert dit SearchCriteria. (geërfd van [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Combineert dit SearchCriteria met andere criteria met behulp van de logische OF-operator. (geërfd van [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (geërfd van [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [vector_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/vector_color_range/) | Het bereik van kleuren dat wordt gebruikt om vectorwatermerken te filteren op voorgrondkleur. |

### Voorbeeld

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

### Zie ook
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
