---
title: to_argb method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Returns the 32-bit ARGB value of this Color structure."
type: docs
url: /python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

Returns the 32-bit ARGB value of this [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) structure.

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### Example

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### See Also
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
