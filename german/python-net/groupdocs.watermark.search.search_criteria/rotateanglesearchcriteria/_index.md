---
title: "Klasse RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt Kriterien dar, die das Filtern nach dem Rotationswinkel des Wasserzeichens ermöglichen."
type: docs
url: /de/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/
is_root: false
weight: 120
---


## RotateAngleSearchCriteria class

Stellt Kriterien dar, die das Filtern nach dem Rotationswinkel des Wasserzeichens ermöglichen.

Mehr erfahren:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

Der Typ RotateAngleSearchCriteria stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/#min_angle-max_angle) | Initialisiert ein neues RotateAngleSearchCriteria mit einem Startwinkel und einem Endwinkel. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Kombiniert dieses SearchCriteria mit anderen Kriterien unter Verwendung des logischen UND-Operators. (geerbt von [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (geerbt von [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Negiert dieses SearchCriteria. (geerbt von [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Kombiniert dieses SearchCriteria mit anderen Kriterien unter Verwendung des logischen ODER-Operators. (geerbt von [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (geerbt von [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [maximum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/maximum_angle/) | Der Endwinkel in Grad. |
| [minimum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/minimum_angle/) | Der Startwinkel in Grad. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

def search_by_angle():
    with Watermarker("./document.pdf") as watermarker:
        angle_criteria = RotateAngleSearchCriteria(30, 60)
        possible = watermarker.search(angle_criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_angle()
```

### Guides
Aufgabenleitfäden, die `RotateAngleSearchCriteria` verwenden:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Siehe auch
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
