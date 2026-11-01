---
title: "search methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Zoekt alle mogelijke watermerken in het document."
type: docs
url: /nl/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

Zoekt alle mogelijke watermerken in het document.

De zoekopdracht wordt uitgevoerd in objecten gespecificeerd in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Meer informatie over het zoeken naar watermerken https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

## search {#search_criteria}

Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria.

De zoekopdracht wordt uitgevoerd in objecten gespecificeerd in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Meer informatie over het zoeken naar watermerken: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | De zoekcriteria om te gebruiken. |

**Returns:** The collection of possible watermarks.

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

### Zie ook
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
