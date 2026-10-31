---
title: "méthode remove"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Supprime un filigrane du document."
type: docs
url: /fr/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

Supprime un filigrane du document.

En savoir plus sur la suppression des filigranes : suppression des filigranes trouvés.

```python
def remove(self, possible_watermark):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | Le filigrane à supprimer. |

### Exemple

```python
from groupdocs.watermark import Watermarker

def remove_first_watermark():
    with Watermarker("./document.pdf") as watermarker:
        watermarks = watermarker.search()
        if watermarks:
            watermarker.remove(watermarks[0])
        watermarker.save("./output.pdf")
```

## remove {#possible_watermarks}

Supprime tous les filigranes de la collection du document.

En savoir plus sur la suppression des filigranes dans la documentation GroupDocs.

```python
def remove(self, possible_watermarks):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | La collection de filigranes à supprimer. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # Supprimez dans l’ordre inverse pour garder les index valides
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### Voir aussi
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
