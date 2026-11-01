---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "指定された画像データを使用して SpreadsheetWatermarkableImage クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

指定された画像データを使用して、[`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) クラスの新しいインスタンスを初期化します。

```python
def __init__(self, image_data):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| image_data | `list[int]` | `SpreadsheetWatermarkableImage` を作成するための符号なしバイト配列です。 |

### 例

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### 関連項目
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
