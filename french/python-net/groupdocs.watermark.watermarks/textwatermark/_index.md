---
title: "Classe TextWatermark"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente un filigrane de texte."
type: docs
url: /fr/python-net/groupdocs.watermark.watermarks/textwatermark/
is_root: false
weight: 110
---


## TextWatermark class

Représente un filigrane de texte.

En savoir plus :
- Adding text watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks

Le type TextWatermark expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/#text-font) | Initialise un nouveau TextWatermark avec le texte et la police spécifiés. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [background_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/background_color/) | La couleur d'arrière-plan du texte. |
| [font](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/font/) | La police du texte. |
| [foreground_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/foreground_color/) | La couleur de premier plan du texte. |
| [padding](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/padding/) | Les paramètres de remplissage de ce TextWatermark, applicables uniquement aux fichiers image. |
| [text](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text/) | Le texte à utiliser comme filigrane. |
| [text_alignment](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text_alignment/) | L’alignement du texte du filigrane. |
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
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Guides
Guides de tâches qui utilisent `TextWatermark`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Voir aussi
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
