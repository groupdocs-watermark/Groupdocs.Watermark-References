---
title: "metodo search"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Cerca tutte le possibili filigrane nel documento."
type: docs
url: /it/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

Cerca tutte le possibili filigrane nel documento.

La ricerca viene eseguita negli oggetti specificati in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Maggiori informazioni sulla ricerca di filigrane https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

### Esempio

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

Cerca le possibili filigrane secondo i criteri di ricerca specificati.

La ricerca viene eseguita negli oggetti specificati in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Maggiori informazioni sulla ricerca di filigrane: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | I criteri di ricerca da utilizzare. |

**Returns:** The collection of possible watermarks.

### Esempio

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

### Vedi anche
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
