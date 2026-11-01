---
title: "get_row_height メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "指定された行の高さ（ポイント）を返します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/get_row_height/
is_root: false
weight: 1050
---


## get_row_height {#row}

指定された行の高さ（ポイント）を返します。

```python
def get_row_height(self, row):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| row | `int` | 行インデックス。 |

**Returns:** float: The height of the row in points.

### 例

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions
    import groupdocs.watermark.contents.spreadsheet as gwc_xls

    load_options = SpreadsheetLoadOptions()
    with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
        content = watermarker.get_content()
        height = content.worksheets[0].get_row_height(0)
        print(height)
    ```

### 関連項目
* class [`SpreadsheetWorksheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/)
