---
title: "classe ImageDctHashSearchCriteria"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta un criterio di ricerca per trovare immagini in un documento."
type: docs
url: /it/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/
is_root: false
weight: 40
---


## ImageDctHashSearchCriteria class

Rappresenta un criterio di ricerca per trovare immagini in un documento.

Questo criterio di ricerca utilizza un hash percettivo dell'immagine basato su DCT per calcolare la somiglianza delle immagini. Per saperne di più: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Il tipo ImageDctHashSearchCriteria espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#file_path) | Inizializza una nuova istanza di ImageDctHashSearchCriteria con un percorso file specificato. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#stream) | Inizializza una nuova istanza di ImageDctHashSearchCriteria con lo stream immagine fornito. |

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
| [max_difference](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/max_difference/) | La differenza massima consentita tra le immagini. (eredita da [`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/)) |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | L'elenco dei numeri di pagina specifici. (eredita da [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### Esempio

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
Guide operative che utilizzano `ImageDctHashSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### Vedi anche
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
