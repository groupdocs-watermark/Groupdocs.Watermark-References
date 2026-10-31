---
title: "méthode to_argb"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Renvoie la valeur ARGB 32 bits de cette structure Color."
type: docs
url: /fr/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

Renvoie la valeur ARGB de 32 bits de cette structure [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/).

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### Exemple

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### Voir aussi
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
