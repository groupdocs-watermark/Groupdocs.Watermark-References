---
title: "add_attachment メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "SpreadsheetWorksheet に添付ファイルを追加します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

SpreadsheetWorksheet に添付ファイルを追加します。

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_content | `list[int]` | 添付されるファイルの内容を含むバイト。 |
| source_full_name | `str` | 添付ファイルの完全な名前（拡張子はファイルを開く適切なアプリケーションを決定するために使用されます）を表す str。 |
| preview_image_content | `list[int]` | 添付ファイルのプレビュー画像をバイト配列として表す bytes。 |
| x | `float` | 添付フレームの x 座標（ポイント単位）を示す int。 |
| y | `float` | 添付フレームの y 座標（ポイント単位）を示す int。 |
| width | `float` | 添付フレームの幅（ポイント単位）を示す int。 |
| height | `float` | 添付フレームの高さ（ポイント単位）を示す int。 |

**Returns:** None.

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

def add_attachment():
    with Watermarker("./sample.xlsx", SpreadsheetLoadOptions()) as watermarker:
        content = watermarker.get_content()
        with open("./sample.docx", "rb") as f:
            data = f.read()
        with open("./preview.png", "rb") as f:
            preview = f.read()
        # ファイルを最初のワークシートに埋め込み、プレビュー画像として表示します
        # x=50、y=20 の位置に、幅100×高さ120 のフレームで
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### 関連項目
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
