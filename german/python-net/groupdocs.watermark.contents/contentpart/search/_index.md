---
title: "search Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien."
type: docs
url: /de/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) aufgeführten Objekten durchgeführt.

```python
def search(self, search_criteria):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Die zu verwendenden Suchkriterien. |

**Returns:** The collection of the possible watermarks.

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

Findet alle möglichen Wasserzeichen im Inhalt.

Die Suche wird in den in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) angegebenen Objekten durchgeführt.

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### Siehe auch
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
