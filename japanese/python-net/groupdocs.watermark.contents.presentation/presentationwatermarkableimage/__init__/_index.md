---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "指定された画像データを使用して PresentationWatermarkableImage クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

指定された画像データを使用して、[`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) クラスの新しいインスタンスを初期化します。

```python
def __init__(self, image_data):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| image_data | `list[int]` | `PresentationWatermarkableImage` を作成するための符号なしバイト配列。 |

### 例

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### 関連項目
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
