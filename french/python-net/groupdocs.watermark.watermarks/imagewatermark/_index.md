---
title: "Classe ImageWatermark"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente un filigrane d'image."
type: docs
url: /fr/python-net/groupdocs.watermark.watermarks/imagewatermark/
is_root: false
weight: 40
---


## ImageWatermark class

Représente un filigrane d'image.

En savoir plus :
- Adding image watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks

Le type ImageWatermark expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#file_path) | Initialise une nouvelle instance d'ImageWatermark avec un chemin de fichier spécifié. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#stream) | Initialise un nouvel ImageWatermark avec le flux d'image fourni. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/dispose/) | Libère l'instance actuelle. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | La propriété indiquant si la taille et les coordonnées du filigrane sont calculées en tenant compte des marges du parent. Si elle est définie sur True, les calculs tiennent compte des marges du parent ; par défaut, la valeur est False et les marges du parent sont ignorées. (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | La hauteur souhaitée de ce [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | L’alignement horizontal de ce Watermark. (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | La propriété indiquant si le filigrane doit être placé en arrière-plan. Si true, le filigrane est placé en bas ; sinon, il est placé en haut (par défaut, False). (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | Les paramètres de marge de ce Watermark. (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | L'opacité de ce [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | Les paramètres de configuration des pages de ce Watermark. (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | L'angle de rotation de ce [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) en degrés. (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | La propriété indique s'il faut enregistrer les informations sur les filigranes ajoutés dans les métadonnées du document. (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | Le facteur d'échelle de ce [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/), définissant comment la taille du filigrane dépend de la taille du parent. (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | Le type de dimensionnement du filigrane. (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | Les options pour définir un filigrane répété. (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | L'alignement vertical de ce [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | La largeur souhaitée de ce [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | La coordonnée x de ce [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | La coordonnée y de ce [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (hérité de [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |

### Exemple

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

def add_image_watermark_from_stream():
    # Charger les données d'image dans un flux
    with open("./logo.png", "rb") as f:
        image_data = f.read()

    # Ouvrir le document et ajouter le filigrane d'image
    with Watermarker("./sample.docx") as watermarker:
        with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
            watermarker.add(watermark)
        watermarker.save("./output.docx")
```

### Guides
Guides de tâches qui utilisent `ImageWatermark` :

* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)

### Voir aussi
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
