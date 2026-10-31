---
title: "Classe ImageColorHistogramSearchCriteria"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta i criteri di ricerca per trovare immagini in un contenuto."
type: docs
url: /it/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/
is_root: false
weight: 30
---


## ImageColorHistogramSearchCriteria class

Rappresenta i criteri di ricerca per trovare immagini in un contenuto.

Questo criterio di ricerca utilizza gli istogrammi di colore dell'immagine per calcolare la somiglianza tra immagini.

Il tipo ImageColorHistogramSearchCriteria espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/__init__/#file_path) | Inizializza una nuova istanza di ImageColorHistogramSearchCriteria con un percorso file specificato. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/__init__/#stream) | Inizializza una nuova istanza di ImageColorHistogramSearchCriteria con uno stream specificato. |

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
| [bins_count](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/bins_count/) | Il numero di bin utilizzati per costruire gli istogrammi di colore. |
| [max_difference](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/max_difference/) | La differenza massima consentita tra le immagini. (eredita da [`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/)) |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | L'elenco dei numeri di pagina specifici. (eredita da [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### Vedi anche
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
