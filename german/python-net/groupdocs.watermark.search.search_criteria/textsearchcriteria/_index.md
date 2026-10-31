---
title: "Klasse TextSearchCriteria"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt Kriterien dar, die das Filtern nach Wasserzeichentext ermöglichen."
type: docs
url: /de/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/
is_root: false
weight: 160
---


## TextSearchCriteria class

Stellt Kriterien dar, die das Filtern nach Wasserzeichentext ermöglichen.

Mehr erfahren:
- [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

Der Typ TextSearchCriteria stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#pattern) | Initialisiert ein neues TextSearchCriteria mit einem angegebenen regulären Ausdruck. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string-is_match_case) | Initialisiert eine neue Instanz der [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) Klasse mit einem Suchstring und einem Flag für die Groß‑/Kleinschreibung‑empfindliche Suche. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string) | Initialisiert eine neue Instanz der [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) Klasse mit einem Suchstring. |

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
| [pattern](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/pattern/) | Das reguläre Ausdrucksmuster, das übereinstimmen soll. |
| [skip_unreadable_characters](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/skip_unreadable_characters/) | Die Eigenschaft, die angibt, ob nicht lesbare Zeichen beim Zeichenfolgenvergleich übersprungen werden. |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | Die Liste der spezifischen Seitenzahlen. (geerbt von [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

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

### Guides
Aufgabenleitfäden, die `TextSearchCriteria` verwenden:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### Siehe auch
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
