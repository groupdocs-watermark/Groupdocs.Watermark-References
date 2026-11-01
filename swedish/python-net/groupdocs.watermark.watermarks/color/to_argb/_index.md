---
title: "to_argb metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Returnerar det 32-bitars ARGB‑värdet för denna Color‑struktur."
type: docs
url: /sv/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

Returnerar det 32‑bitars ARGB‑värdet för denna [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) struktur.

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### Exempel

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### Se även
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
