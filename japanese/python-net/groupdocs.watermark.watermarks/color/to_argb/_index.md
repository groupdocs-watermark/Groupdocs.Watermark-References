---
title: "to_argb メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "この Color 構造体の 32 ビット ARGB 値を返します。"
type: docs
url: /ja/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

この [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) 構造体の 32 ビット ARGB 値を返します。

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### 例

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### 関連項目
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
