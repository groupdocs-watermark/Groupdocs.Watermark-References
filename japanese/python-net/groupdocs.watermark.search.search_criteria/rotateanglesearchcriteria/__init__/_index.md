---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "開始角度と終了角度を指定して新しい RotateAngleSearchCriteria を初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

開始角度と終了角度を指定して新しい RotateAngleSearchCriteria を初期化します。

```python
def __init__(self, min_angle, max_angle):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| min_angle | `float` | 開始角度（度）です。 |
| max_angle | `float` | 終了角度（度）です。 |

### 例

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# 30 度から 60 度の間で回転した透かしを検索します
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### 関連項目
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
