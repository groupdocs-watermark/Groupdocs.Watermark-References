---
title: "classe TextSearchCriteria"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta i criteri che consentono il filtraggio per testo del watermark."
type: docs
url: /it/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/
is_root: false
weight: 160
---


## TextSearchCriteria class

Rappresenta i criteri che consentono il filtraggio per testo del watermark.

Per saperne di più:
- [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

Il tipo TextSearchCriteria espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#pattern) | Inizializza un nuovo TextSearchCriteria con un'espressione regolare specificata. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string-is_match_case) | Inizializza una nuova istanza della classe [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) con una stringa di ricerca e un flag per il confronto sensibile al maiuscolo/minuscolo. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string) | Inizializza una nuova istanza della classe [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) con una stringa di ricerca. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Combina questo SearchCriteria con altri criteri usando l'operatore logico AND. (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Negare questo SearchCriteria. (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Combina questo SearchCriteria con altri criteri usando l'operatore logico OR. (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [pattern](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/pattern/) | Il modello di espressione regolare da corrispondere. |
| [skip_unreadable_characters](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/skip_unreadable_characters/) | La proprietà che indica se i caratteri illeggibili vengono saltati durante il confronto delle stringhe. |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | L'elenco dei numeri di pagina specifici. (eredita da [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### Esempio

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
Guide operative che utilizzano `TextSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### Vedi anche
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
