---
title: "to_argb methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Retourneert de 32‑bit ARGB‑waarde van deze Color‑structuur."
type: docs
url: /nl/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

Retourneert de 32-bits ARGB‑waarde van deze [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) structuur.

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### Zie ook
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
