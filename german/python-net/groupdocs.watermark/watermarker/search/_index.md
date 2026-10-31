---
title: "search Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Durchsucht alle möglichen Wasserzeichen im Dokument."
type: docs
url: /de/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

Durchsucht alle möglichen Wasserzeichen im Dokument.

Die Suche wird in Objekten durchgeführt, die in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) angegeben sind.

Erfahren Sie mehr über das Suchen von Wasserzeichen https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

### Beispiel

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

Durchsucht mögliche Wasserzeichen gemäß den angegebenen Suchkriterien.

Die Suche wird in Objekten durchgeführt, die in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) angegeben sind.

Erfahren Sie mehr über das Suchen von Wasserzeichen: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Die zu verwendenden Suchkriterien. |

**Returns:** The collection of possible watermarks.

### Beispiel

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

### Siehe auch
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
