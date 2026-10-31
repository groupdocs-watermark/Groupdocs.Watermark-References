---
title: "metodo search"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Trova i possibili watermark in base ai criteri di ricerca specificati."
type: docs
url: /it/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

Trova i possibili watermark secondo i criteri di ricerca specificati. La ricerca viene eseguita sugli oggetti elencati in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def search(self, search_criteria):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | I criteri di ricerca da utilizzare. |

**Returns:** The collection of the possible watermarks.

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

Trova tutti i possibili watermark nel contenuto.

La ricerca viene eseguita negli oggetti specificati in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### Vedi anche
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
