---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise un nouveau TextWatermark avec le texte et la police spécifiés."
type: docs
url: /fr/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text-font}

Initialise un nouveau TextWatermark avec le texte et la police spécifiés.

```python
def __init__(self, text, font):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Le texte à utiliser comme filigrane. |
| font | `Font` | La police du texte. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Voir aussi
* class [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)
