---
title: "MeasureValue クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "特定の型と数値を持つ測定値を表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

特定の型と数値を持つ測定値を表します。

MeasureValue 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | 測定の種類です。 |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | 測定の数値; 0 より大きくなければなりません。 |

### 例

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# ページのパーセンテージとして表される測定を作成する
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
`MeasureValue` を使用するタスク ガイド:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### 関連項目
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
