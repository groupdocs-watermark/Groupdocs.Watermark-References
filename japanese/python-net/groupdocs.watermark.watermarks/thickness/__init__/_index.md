---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "矩形の各側面に特定の長さを適用した新しい Thickness インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.watermarks/thickness/__init__/
is_root: false
weight: 10
---


## __init__ {#left-right-top-bottom}

矩形の各側面に特定の長さを適用した新しい Thickness インスタンスを初期化します。

```python
def __init__(self, left, right, top, bottom):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| left | `float` | 矩形の左側の厚さです。 |
| right | `float` | 矩形の右側の厚さです。 |
| top | `float` | 矩形の上側の厚さです。 |
| bottom | `float` | 矩形の下側の厚さです。 |

## __init__ {#uniform_length}

各側面に指定された均一な長さを持つ新しい Thickness インスタンスを初期化します。

```python
def __init__(self, uniform_length):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| uniform_length | `float` | バウンディング矩形の4辺すべてに適用される均一な長さです。 |

### 関連項目
* class [`Thickness`](/watermark/python-net/groupdocs.watermark.watermarks/thickness/)
