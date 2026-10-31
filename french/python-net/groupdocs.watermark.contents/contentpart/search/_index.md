---
title: "méthode search"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Trouve les filigranes possibles selon les critères de recherche spécifiés."
type: docs
url: /fr/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

Recherche les filigranes possibles selon les critères de recherche spécifiés. La recherche est effectuée sur les objets répertoriés dans [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def search(self, search_criteria):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Les critères de recherche à utiliser. |

**Returns:** The collection of the possible watermarks.

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

Recherche tous les filigranes possibles dans le contenu.

La recherche est effectuée dans les objets spécifiés dans [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### Voir aussi
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
