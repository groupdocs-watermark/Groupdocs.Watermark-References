---
title: "search methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Vindt mogelijke watermerken volgens de opgegeven zoekcriteria."
type: docs
url: /nl/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd op de objecten die zijn vermeld in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def search(self, search_criteria):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | De zoekcriteria om te gebruiken. |

**Returns:** The collection of the possible watermarks.

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

Zoekt alle mogelijke watermerken in de inhoud.

De zoekopdracht wordt uitgevoerd in de objecten die zijn opgegeven in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### Zie ook
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
