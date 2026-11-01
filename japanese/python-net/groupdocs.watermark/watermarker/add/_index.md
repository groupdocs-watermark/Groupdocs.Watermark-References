---
title: "add メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "読み込まれたドキュメントに透かしを追加します。"
type: docs
url: /ja/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

読み込まれたドキュメントに透かしを追加します。

GroupDocs のドキュメントで透かしの追加に関する詳細をご覧ください。

```python
def add(self, watermark):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| watermark | `Watermark` | ドキュメントに追加する透かしです。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

## add {#watermark-options}

透かしオプションを使用して読み込まれたドキュメントに透かしを追加します。

透かしの追加に関する詳細はこちら: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| watermark | `Watermark` | ドキュメントに追加する透かしです。 |
| options | `WatermarkOptions` | 透かしを追加する際に使用する追加オプションです。 |

**Returns:** None.

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### 関連項目
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
