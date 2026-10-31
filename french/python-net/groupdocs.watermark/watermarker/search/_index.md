---
title: "méthode search"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Recherche tous les filigranes possibles dans le document."
type: docs
url: /fr/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

Recherche tous les filigranes possibles dans le document.

La recherche est effectuée dans les objets spécifiés dans [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

En savoir plus sur la recherche de filigranes https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

### Exemple

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

Recherche les filigranes possibles selon les critères de recherche spécifiés.

La recherche est effectuée dans les objets spécifiés dans [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

En savoir plus sur la recherche de filigranes : https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Les critères de recherche à utiliser. |

**Returns:** The collection of possible watermarks.

### Exemple

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

### Voir aussi
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
