---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "ColorRange クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

新しい [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) クラスのインスタンスを初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# デフォルトのカラー範囲を作成します
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

指定された正確な色で新しい [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) のインスタンスを初期化します。

```python
def __init__(self, exact_color):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| exact_color | `Color` | 範囲が作成される正確な色です。 |

### 関連項目
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
