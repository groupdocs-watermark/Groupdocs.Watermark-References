---
title: "to_argb metode"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mengembalikan nilai ARGB 32-bit dari struktur Color ini."
type: docs
url: /id/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

Mengembalikan nilai ARGB 32-bit dari struktur [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) ini.

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### Contoh

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### Lihat Juga
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
