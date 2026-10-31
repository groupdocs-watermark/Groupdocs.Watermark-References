---
title: "Classe Watermarker"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente une classe pour la gestion des filigranes dans un document."
type: docs
url: /fr/python-net/groupdocs.watermark/watermarker/
is_root: false
weight: 60
---


## Watermarker class

Représente une classe pour la gestion des filigranes dans un document.

Chargez et enregistrez le contenu de tout format pris en charge.

Le type Watermarker expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path) | Initialise une nouvelle instance de Watermarker avec le chemin de document spécifié. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-options) | Initialise une nouvelle instance de Watermarker avec le chemin de document spécifié et les options de chargement. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-settings) | Initialise un Watermarker avec le chemin de document spécifié et les paramètres. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-options-settings) | Initialise une nouvelle instance de Watermarker avec le chemin de document spécifié, les options de chargement et les paramètres. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document) | Initialise une nouvelle instance de la classe Watermarker avec le flux spécifié. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-options) | Initialise une nouvelle instance de Watermarker avec le flux spécifié et les options de chargement. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-settings) | Initialise une nouvelle instance de Watermarker avec le flux spécifié et les paramètres. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-options-settings) | Initialise une nouvelle instance de la classe [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) avec le flux spécifié, les options de chargement et les paramètres. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark/watermarker/add/#watermark) | Ajoute un filigrane au document chargé. |
| [add](/watermark/python-net/groupdocs.watermark/watermarker/add/#watermark-options) | Ajoute un filigrane au document chargé en utilisant les options de filigrane. |
| [add_watermark](/watermark/python-net/groupdocs.watermark/watermarker/add_watermark/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark/watermarker/dispose/) | Libère l'instance actuelle. |
| [generate_preview](/watermark/python-net/groupdocs.watermark/watermarker/generate_preview/#preview_options) | Génère des images d'aperçu pour le document. |
| [generate_preview_preview_options](/watermark/python-net/groupdocs.watermark/watermarker/generate_preview_preview_options/) |  |
| [get_content](/watermark/python-net/groupdocs.watermark/watermarker/get_content/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark/watermarker/get_document_info/) | Obtient les informations sur le format du document chargé. |
| [get_images](/watermark/python-net/groupdocs.watermark/watermarker/get_images/#search_criteria) | Trouve les images selon les critères de recherche spécifiés. |
| [get_images](/watermark/python-net/groupdocs.watermark/watermarker/get_images/) | Trouve toutes les images du document. |
| [get_images_image_search_criteria](/watermark/python-net/groupdocs.watermark/watermarker/get_images_image_search_criteria/) |  |
| [remove](/watermark/python-net/groupdocs.watermark/watermarker/remove/#possible_watermark) | Supprime un filigrane du document. |
| [remove](/watermark/python-net/groupdocs.watermark/watermarker/remove/#possible_watermarks) | Supprime tous les filigranes de la collection du document. |
| [remove_possible_watermark](/watermark/python-net/groupdocs.watermark/watermarker/remove_possible_watermark/) |  |
| [remove_possible_watermark_collection](/watermark/python-net/groupdocs.watermark/watermarker/remove_possible_watermark_collection/) |  |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/) | Enregistre les données du document dans le flux sous-jacent. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#file_path) | Enregistre le document à l'emplacement de fichier spécifié. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#document) | Enregistre le document dans le flux spécifié. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#options) | Enregistre les données du document dans le flux sous-jacent en utilisant les options d'enregistrement. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#file_path-options) | Enregistre le document à l'emplacement de fichier spécifié en utilisant les options d'enregistrement. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#document-options) | Enregistre le document dans le flux spécifié en utilisant les options d'enregistrement. |
| [save_file](/watermark/python-net/groupdocs.watermark/watermarker/save_file/) |  |
| [save_save_options](/watermark/python-net/groupdocs.watermark/watermarker/save_save_options/) |  |
| [save_stream](/watermark/python-net/groupdocs.watermark/watermarker/save_stream/) |  |
| [save_streams](/watermark/python-net/groupdocs.watermark/watermarker/save_streams/) |  |
| [save_string](/watermark/python-net/groupdocs.watermark/watermarker/save_string/) |  |
| [search](/watermark/python-net/groupdocs.watermark/watermarker/search/) | Recherche tous les filigranes possibles dans le document. |
| [search](/watermark/python-net/groupdocs.watermark/watermarker/search/#search_criteria) | Recherche les filigranes possibles selon les critères de recherche spécifiés. |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark/watermarker/search_search_criteria/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) | Les objets qui doivent être inclus dans une recherche de filigrane. |

### Exemple

```python
from groupdocs.watermark import Watermarker

with Watermarker("D:\\input.pdf") as watermarker:
    # Utilisez les méthodes de `Watermarker` pour ajouter, rechercher ou supprimer des filigranes.
    watermarker.save("D:\\output.pdf")
```

### Guides
Guides de tâches qui utilisent `Watermarker` :

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)
* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)
* [Document preview](/watermark/python-net/guides/preview/)
* [Get document info](/watermark/python-net/guides/get-document-info/)

### Voir aussi
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
