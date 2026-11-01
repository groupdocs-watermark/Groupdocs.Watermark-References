---
title: "Attachment クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "ドキュメントに添付されたファイルを表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

ドキュメントに添付されたファイルを表します。

詳細を見る

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

Attachment 型は次のメンバーを公開します：

### メソッド
| メソッド | 説明 |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | 添付ファイルからコンテンツを読み込みます。 |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | 指定されたロードオプションを使用して、添付ファイルからコンテンツを読み込みます。 |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | 指定されたロードオプションと設定を使用して、添付ファイルからコンテンツを読み込みます。 |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | 添付ファイルに保存されているドキュメントに関する情報を取得します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | 添付ファイルのコンテンツ。 |

### 例

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.pdf import PdfLoadOptions
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww
from groupdocs.watermark.common import FileType

watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))
load_options = PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    pdf_content = watermarker.get_content()
    for attachment in pdf_content.attachments:
        info = attachment.get_document_info()
        if info.file_type != FileType.UNKNOWN and not info.is_encrypted:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    watermarker.save("output.pdf")
```

### 関連項目
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
