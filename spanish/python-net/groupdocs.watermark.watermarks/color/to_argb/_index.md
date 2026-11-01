---
title: "método to_argb"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Devuelve el valor ARGB de 32 bits de esta estructura Color."
type: docs
url: /es/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

Devuelve el valor ARGB de 32 bits de esta estructura [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/).

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### Ejemplo

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### Ver también
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
