---
title: "طريقة to_argb"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يعيد قيمة ARGB 32‑بت لهذا الهيكل Color."
type: docs
url: /ar/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

يرجع قيمة ARGB 32‑بت لهذا الهيكل [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/).

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### مثال

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### انظر أيضًا
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
