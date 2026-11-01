---
title: "search yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen arama kriterlerine göre olası filigranları bulur."
type: docs
url: /tr/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

Belirtilen arama kriterlerine göre olası filigranları bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) listesinde yer alan nesneler üzerinde gerçekleştirilir.

```python
def search(self, search_criteria):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Kullanılacak arama kriteri. |

**Returns:** The collection of the possible watermarks.

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

İçerikteki tüm olası filigranları bulur.

Arama, [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) içinde belirtilen nesnelerde gerçekleştirilir.

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### Ayrıca Bakınız
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
