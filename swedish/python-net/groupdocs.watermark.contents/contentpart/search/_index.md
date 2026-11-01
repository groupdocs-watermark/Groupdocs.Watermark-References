---
title: "search‑metoden"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Hittar möjliga vattenmärken enligt de angivna sökkriterierna."
type: docs
url: /sv/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

Hittar möjliga vattenstämplar enligt de angivna sökkriterierna. Sökningen utförs på de objekt som listas i [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def search(self, search_criteria):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Sök kriterierna att använda. |

**Returns:** The collection of the possible watermarks.

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

Hittar alla möjliga vattenstämplar i innehållet.

Sökningen utförs i de objekt som anges i [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### Se även
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
