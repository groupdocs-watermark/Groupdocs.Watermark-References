---
title: "search yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belgedeki olası tüm filigranları arar."
type: docs
url: /tr/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

Belgedeki olası tüm filigranları arar.

Arama, [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) içinde belirtilen nesnelerde gerçekleştirilir.

Filigran arama hakkında daha fazla bilgi edinin https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

### Örnek

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

Belirtilen arama kriterlerine göre olası filigranları arar.

Arama, [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) içinde belirtilen nesnelerde gerçekleştirilir.

Filigran arama hakkında daha fazla bilgi edinin: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Kullanılacak arama kriteri. |

**Returns:** The collection of possible watermarks.

### Örnek

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

### Ayrıca Bakınız
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
