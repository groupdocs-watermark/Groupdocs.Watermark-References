---
title: "ColorRange クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "RGB カラーの HSB 表現を使用した色の範囲を表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

RGB カラーの HSB 表現を使用した色の範囲を表します。

ColorRange 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | 新しい [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) クラスのインスタンスを初期化します。 |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | 指定された正確な色で新しい [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) のインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | 空の色のみが範囲内にあるかどうかを示すフラグです。 |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | 終了時の明度値で、0.0（黒）から1.0（白）までの範囲です。 |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | 終了時の色相値（度）です。 |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | 終了時の彩度値です。 |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | 開始時の明度値で、0.0（黒）から1.0（白）までの範囲です。 |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | 開始時の色相値（度）です。 |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | 開始時の彩度値です。 |

### 例

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# 前景色のマッチング用にカラーレンジを作成します
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
`ColorRange` を使用するタスクガイド:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### 関連項目
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
