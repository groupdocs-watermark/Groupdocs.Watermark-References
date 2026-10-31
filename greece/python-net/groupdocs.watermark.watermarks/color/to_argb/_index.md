---
title: "to_argb μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Επιστρέφει την 32-bit τιμή ARGB αυτής της δομής Color."
type: docs
url: /el/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

Επιστρέφει την 32‑bit τιμή ARGB αυτής της δομής [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/).

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### Δείτε επίσης
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
