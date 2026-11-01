---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "指定された画像データを使用して DiagramWatermarkableImage クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

指定された画像データを使用して [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) クラスの新しいインスタンスを初期化します。

```python
def __init__(self, image_data):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| image_data | `list[int]` | `DiagramWatermarkableImage` を作成するための符号なしバイトの配列です。 |

### 例

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

with open("test.png", "rb") as f:
    img = gwc_vsdx.DiagramWatermarkableImage(f.read())
```

### 関連項目
* class [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/)
