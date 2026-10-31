---
title: "Classe ImageColorHistogramSearchCriteria"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente les critères de recherche pour trouver des images dans un contenu."
type: docs
url: /fr/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/
is_root: false
weight: 30
---


## ImageColorHistogramSearchCriteria class

Représente les critères de recherche pour trouver des images dans un contenu.

Ce critère de recherche utilise des histogrammes de couleur d'image pour calculer la similarité d'images.

Le type ImageColorHistogramSearchCriteria expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/__init__/#file_path) | Initialise une nouvelle instance de ImageColorHistogramSearchCriteria avec un chemin de fichier spécifié. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/__init__/#stream) | Initialise une nouvelle instance de ImageColorHistogramSearchCriteria avec un flux spécifié. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Combine ce SearchCriteria avec d'autres critères en utilisant l'opérateur logique AND. (hérité de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (hérité de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Négate ce SearchCriteria. (hérité de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Combine ce SearchCriteria avec d'autres critères en utilisant l'opérateur logique OR. (hérité de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (hérité de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [bins_count](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/bins_count/) | Le nombre de compartiments utilisés pour créer les histogrammes de couleur. |
| [max_difference](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/max_difference/) | La différence maximale autorisée entre les images. (hérité de [`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/)) |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | La liste des numéros de page spécifiques. (hérité de [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### Voir aussi
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
