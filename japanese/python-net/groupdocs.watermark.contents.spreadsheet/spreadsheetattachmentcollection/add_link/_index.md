---
title: "add_link メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "リンクで添付ファイルを追加します（ドキュメントには添付ファイルの内容が含まれません）。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

リンクで添付ファイルを追加します（ドキュメントには添付ファイルの内容が含まれません）。

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| source_full_name | `str` | リンクされたファイルパス。 |
| preview_image_content | `list[int]` | 添付ファイルのプレビュー画像（バイト配列）です。 |
| x | `float` | 添付フレームの x 座標（ポイント単位）。 |
| y | `float` | 添付フレームの y 座標（ポイント単位）。 |
| width | `float` | 添付フレームの幅（ポイント単位）です。 |
| height | `float` | ポイント単位の添付フレームの高さです。 |

### 例

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions
import groupdocs.watermark.contents.spreadsheet as gwc_xls

load_options = SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    content = watermarker.get_content()
    worksheet = content.worksheets[0]
    with open("document_preview.png", "rb") as f_prev:
        worksheet.attachments.add_link(
            "document.docx",
            f_prev.read(),
            50,
            100,
            200,
            400,
        )
    watermarker.save("output.xlsx")
```

### 関連項目
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
