---
title: "classe HyperlinkPossibleWatermark"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente un filigrane hyperlien possible dans un contenu PowerPoint."
type: docs
url: /fr/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/
is_root: false
weight: 60
---


## HyperlinkPossibleWatermark class

Représente un filigrane hyperlien possible dans un contenu PowerPoint.

Le type HyperlinkPossibleWatermark expose les membres suivants:

### Propriétés
| Propriété | Description |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/height/) | La hauteur de ce HyperlinkPossibleWatermark. |
| [parent](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/parent/) | Le parent de ce HyperlinkPossibleWatermark. |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/rotate_angle/) | L'angle de rotation de ce HyperlinkPossibleWatermark en degrés. |
| [text](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/text/) | L'URL de ce HyperlinkPossibleWatermark. |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/unit_of_measurement/) | L'unité de mesure de ce [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [width](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/width/) | La largeur de ce HyperlinkPossibleWatermark. |
| [x](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/x/) | La coordonnée x de ce HyperlinkPossibleWatermark. |
| [y](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/y/) | La coordonnée y de ce [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | La collection de fragments de texte formatés de ce [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (hérité de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | L'image de ce [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) ou None si le filigrane n'a pas d'image. (hérité de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | Le numéro de page où le filigrane est placé. (hérité de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |

### Exemple

```python
import re
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search import HyperlinkPossibleWatermark
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria(re.compile(r"someurl\.com")))
    for i in range(len(possible) - 1, -1, -1):
        if isinstance(possible[i], HyperlinkPossibleWatermark):
            print(possible[i].text)
            watermarker.remove(possible[i])
    watermarker.save("./output.pdf")
```

### Voir aussi
* module [`groupdocs.watermark.search`](/watermark/python-net/groupdocs.watermark.search/)
