---
title: "remove Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Entfernt ein Wasserzeichen aus dem Dokument."
type: docs
url: /de/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

Entfernt ein Wasserzeichen aus dem Dokument.

Erfahren Sie mehr über das Entfernen von Wasserzeichen: Gefundene Wasserzeichen entfernen.

```python
def remove(self, possible_watermark):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | Das zu entfernende Wasserzeichen. |

### Beispiel

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

Entfernt alle Wasserzeichen aus der Sammlung im Dokument.

Erfahren Sie mehr über das Entfernen von Wasserzeichen in der GroupDocs-Dokumentation.

```python
def remove(self, possible_watermarks):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | Die Sammlung von zu entfernenden Wasserzeichen. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # Entfernen Sie in umgekehrter Reihenfolge, um die Indizes gültig zu halten.
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### Siehe auch
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
