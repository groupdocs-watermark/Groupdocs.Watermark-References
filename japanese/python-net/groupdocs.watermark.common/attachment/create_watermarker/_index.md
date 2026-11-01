---
title: "create_watermarker メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "添付ファイルからコンテンツを読み込みます。"
type: docs
url: /ja/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

添付ファイルからコンテンツを読み込みます。

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### 例

```python
    import groupdocs.watermark as gw
    import groupdocs.watermark.contents.pdf as gwc_pdf
    import groupdocs.watermark.watermarks as gww

    watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))

    with gw.Watermarker("document.pdf") as watermarker:
        pdf_content = watermarker.get_content()
        for attachment in pdf_content.attachments:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    ```

## create_watermarker {#load_options}

指定されたロードオプションを使用して、添付ファイルからコンテンツを読み込みます。

```python
def create_watermarker(self, load_options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| load_options | `LoadOptions` | 添付コンテンツを読み込む際に使用する追加オプション。 |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

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

## create_watermarker {#load_options-watermarker_settings}

指定されたロードオプションと設定を使用して、添付ファイルからコンテンツを読み込みます。

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| load_options | `LoadOptions` | 添付コンテンツを読み込む際に使用する追加オプション。 |
| watermarker_settings | `WatermarkerSettings` | 読み込んだドキュメントを操作する際に使用する追加設定。 |

**Returns:** The instance of appropriate descendant of `Content` class.

### 例

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww

watermark = gww.TextWatermark("Sample watermark", gww.Font("Arial", 19.0))

with gw.Watermarker("document.pdf") as watermarker:
    pdf_content = watermarker.get_content()
    for attachment in pdf_content.attachments:
        with attachment.create_watermarker() as attached:
            attached.add(watermark)
            attached.save()
    watermarker.save("output.pdf")
```

### 関連項目
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
