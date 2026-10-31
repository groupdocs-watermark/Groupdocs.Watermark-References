---
title: "to_argb मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "वापस करता है 32-बिट ARGB मान इस Color संरचना का।"
type: docs
url: /hi/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

इस [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) संरचना का 32-बिट ARGB मान लौटाता है।

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### उदाहरण

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### संबंधित देखें
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
