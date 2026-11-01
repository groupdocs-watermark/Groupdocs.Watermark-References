---
title: "search‑metoden"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Söker igenom alla möjliga vattenmärken i dokumentet."
type: docs
url: /sv/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

Söker igenom alla möjliga vattenmärken i dokumentet.

Sökningen utförs i objekt som anges i [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Läs mer om att söka efter vattenstämplar https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

### Exempel

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

Söker möjliga vattenmärken enligt angivna sökkriterier.

Sökningen utförs i objekt som anges i [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Läs mer om att söka efter vattenstämplar: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Sök kriterierna att använda. |

**Returns:** The collection of possible watermarks.

### Exempel

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

### Se även
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
