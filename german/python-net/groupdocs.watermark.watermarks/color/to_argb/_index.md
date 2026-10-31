---
title: "to_argb Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Gibt den 32‑Bit‑ARGB‑Wert dieser Color‑Struktur zurück."
type: docs
url: /de/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

Gibt den 32‑Bit‑ARGB‑Wert dieser [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) Struktur zurück.

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### Beispiel

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### Siehe auch
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
