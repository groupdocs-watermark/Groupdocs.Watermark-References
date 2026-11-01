---
title: "to_argb метод"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Возвращает 32‑битное значение ARGB этой структуры Color."
type: docs
url: /ru/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

Возвращает 32‑битное значение ARGB этой структуры [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/).

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### Пример

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### См. также
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
