---
title: "to_argb metodu"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bu Color yapısının 32-bit ARGB değerini döndürür."
type: docs
url: /tr/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

Bu [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) yapısının 32 bitlik ARGB değerini döndürür.

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### Örnek

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### Ayrıca Bakınız
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
