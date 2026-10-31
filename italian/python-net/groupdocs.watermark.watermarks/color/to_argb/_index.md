---
title: "metodo to_argb"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Restituisce il valore ARGB a 32 bit di questa struttura Color."
type: docs
url: /it/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

Restituisce il valore ARGB a 32‑bit di questa struttura [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/).

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### Esempio

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### Vedi anche
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
