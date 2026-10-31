---
title: "to_argb 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "返回此 Color 结构的 32 位 ARGB 值。"
type: docs
url: /zh/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

返回此 [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) 结构的 32 位 ARGB 值。

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### 示例

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### 另请参见
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
