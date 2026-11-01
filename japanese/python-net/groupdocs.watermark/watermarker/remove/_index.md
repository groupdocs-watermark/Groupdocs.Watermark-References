---
title: "remove メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "ドキュメントから透かしを削除します。"
type: docs
url: /ja/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

ドキュメントから透かしを削除します。

透かしの削除について詳しく見る: 見つかった透かしの削除。

```python
def remove(self, possible_watermark):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | 削除する透かし。 |

### 例

```python
from groupdocs.watermark import Watermarker

def remove_first_watermark():
    with Watermarker("./document.pdf") as watermarker:
        watermarks = watermarker.search()
        if watermarks:
            watermarker.remove(watermarks[0])
        watermarker.save("./output.pdf")
```

## remove {#possible_watermarks}

コレクション内のすべての透かしをドキュメントから削除します。

GroupDocs のドキュメントで透かしの削除について詳しく見る。

```python
def remove(self, possible_watermarks):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | 削除する透かしのコレクション。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # インデックスを有効に保つために逆順で削除する
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### 関連項目
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
