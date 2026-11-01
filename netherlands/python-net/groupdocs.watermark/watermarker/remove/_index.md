---
title: "remove-methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Verwijdert een watermerk uit het document."
type: docs
url: /nl/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

Verwijdert een watermerk uit het document.

Meer informatie over het verwijderen van watermerken: Verwijderen van gevonden watermerken.

```python
def remove(self, possible_watermark):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | Het watermerk om te verwijderen. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker

def remove_first_watermark():
    with Watermarker("./document.pdf") as watermarker:
        watermarks = watermarker.search()
        if watermarks:
            watermarker.remove(watermarks[0])
        watermarker.save("./output.pdf")
```

## remove {#possible_watermarks}

Verwijdert alle watermerken in de collectie uit het document.

Meer informatie over het verwijderen van watermerken in de GroupDocs-documentatie.

```python
def remove(self, possible_watermarks):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | De verzameling watermerken om te verwijderen. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # Verwijder in omgekeerde volgorde om indexen geldig te houden
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### Zie ook
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
