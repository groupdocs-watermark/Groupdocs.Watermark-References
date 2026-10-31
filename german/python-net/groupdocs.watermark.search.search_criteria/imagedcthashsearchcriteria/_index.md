---
title: "Klasse ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt ein Suchkriterium zum Finden von Bildern in einem Dokument dar."
type: docs
url: /de/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/
is_root: false
weight: 40
---


## ImageDctHashSearchCriteria class

Stellt ein Suchkriterium zum Finden von Bildern in einem Dokument dar.

Dieses Suchkriterium verwendet einen DCT‑basierten perceptuellen Bild‑Hash zur Berechnung der Bildähnlichkeit. Weitere Informationen: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Der Typ ImageDctHashSearchCriteria stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#file_path) | Initialisiert eine neue ImageDctHashSearchCriteria‑Instanz mit einem angegebenen Dateipfad. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#stream) | Initialisiert eine neue ImageDctHashSearchCriteria‑Instanz mit dem bereitgestellten Bildstrom. |

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
| [max_difference](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/max_difference/) | Der maximal zulässige Unterschied zwischen Bildern. (geerbt von [`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/)) |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | Die Liste der spezifischen Seitenzahlen. (geerbt von [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")
```

### Guides
Aufgabenleitfäden, die `ImageDctHashSearchCriteria` verwenden:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### Siehe auch
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
