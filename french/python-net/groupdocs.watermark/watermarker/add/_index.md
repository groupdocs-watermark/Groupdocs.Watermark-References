---
title: "méthode add"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Ajoute un filigrane au document chargé."
type: docs
url: /fr/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

Ajoute un filigrane au document chargé.

En savoir plus sur l'ajout de filigranes dans la documentation GroupDocs.

```python
def add(self, watermark):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| watermark | `Watermark` | Le filigrane à ajouter au document. |

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

## add {#watermark-options}

Ajoute un filigrane au document chargé en utilisant les options de filigrane.

En savoir plus sur l'ajout de filigranes : https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| watermark | `Watermark` | Le filigrane à ajouter au document. |
| options | `WatermarkOptions` | Options supplémentaires à utiliser lors de l'ajout du filigrane. |

**Returns:** None.

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

### Voir aussi
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
