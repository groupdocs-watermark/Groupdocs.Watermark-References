---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "指定されたテキストとフォントで新しい TextWatermark を初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text-font}

指定されたテキストとフォントで新しい TextWatermark を初期化します。

```python
def __init__(self, text, font):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| text | `str` | 透かしとして使用されるテキストです。 |
| font | `Font` | テキストのフォントです。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### 関連項目
* class [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)
