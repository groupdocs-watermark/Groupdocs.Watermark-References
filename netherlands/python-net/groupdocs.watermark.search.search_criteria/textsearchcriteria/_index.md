---
title: "TextSearchCriteria klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt criteria voor die filteren op watermerktekst."
type: docs
url: /nl/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/
is_root: false
weight: 160
---


## TextSearchCriteria class

Stelt criteria voor die filteren op watermerktekst.

Meer informatie:
- [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

Het type TextSearchCriteria bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#pattern) | Initialiseert een nieuwe TextSearchCriteria met een opgegeven reguliere expressie. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string-is_match_case) | Initialiseert een nieuwe instantie van de [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) klasse met een zoekstring en een vlag voor hoofdlettergevoelige vergelijking. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string) | Initialiseert een nieuwe instantie van de [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) klasse met een zoekstring. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Combineert dit SearchCriteria met andere criteria met behulp van de logische EN-operator. (geërfd van [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (geërfd van [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Negereert dit SearchCriteria. (geërfd van [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Combineert dit SearchCriteria met andere criteria met behulp van de logische OF-operator. (geërfd van [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (geërfd van [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [pattern](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/pattern/) | Het patroon van de reguliere expressie om te matchen. |
| [skip_unreadable_characters](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/skip_unreadable_characters/) | De eigenschap die aangeeft of onleesbare tekens worden overgeslagen tijdens de tekenreeksvergelijking. |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | De lijst met specifieke paginanummers. (geërfd van [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### Voorbeeld

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
Taakgidsen die `TextSearchCriteria` gebruiken:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### Zie ook
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
