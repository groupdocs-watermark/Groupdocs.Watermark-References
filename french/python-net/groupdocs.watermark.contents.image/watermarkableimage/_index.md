---
title: "Classe WatermarkableImage"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente une image à l'intérieur d'un document."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.image/watermarkableimage/
is_root: false
weight: 90
---


## WatermarkableImage class

Représente une image à l'intérieur d'un document.

En savoir plus :
- https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document

Le type WatermarkableImage expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/#watermark) | Ajoute un filigrane à ce [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). Cette méthode suppose que le décalage et la taille du filigrane sont mesurés en pixels (s'ils sont définis). |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) |  |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Obtient l'image sous forme de tableau d'octets. |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Recherche des images selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (hérité de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (hérité de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Recherche les filigranes possibles selon les critères de recherche spécifiés. La recherche est effectuée sur les objets répertoriés dans [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (hérité de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (hérité de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | La hauteur de ce [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) en pixels. |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | La largeur de ce WatermarkableImage en pixels. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker(r"D:\input.doc") as watermarker:
    # Initialiser le filigrane texte.
    watermark = TextWatermark("DRAFT", Font("Arial", 19))

    # Trouver toutes les images dans le document.
    images = watermarker.get_images()

    # Ajouter un filigrane à chaque image.
    for img in images:
        img.add(watermark)

    # Enregistrer les modifications.
    watermarker.save(r"D:\output.doc")
```

### Voir aussi
* module [`groupdocs.watermark.contents.image`](/watermark/python-net/groupdocs.watermark.contents.image/)
