---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "PdfLoadOptions クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

[`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) クラスの新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.pdf import PdfLoadOptions
import groupdocs.watermark.contents.pdf as gwc_pdf

load_options = PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    pdf_content = watermarker.get_content()
    print(pdf_content.pages[0].width)
    print(pdf_content.pages[0].height)
```

## __init__ {#password}

指定されたパスワードで、[`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) クラスの新しいインスタンスを初期化します。

```python
def __init__(self, password):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| password | `str` | 暗号化されたドキュメントを開くためのパスワードです。 |

### 例

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.pdf import PdfLoadOptions
import groupdocs.watermark.contents.pdf as gwc_pdf

load_options = PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    pdf_content = watermarker.get_content()
    print(pdf_content.pages[0].width)
    print(pdf_content.pages[0].height)
```

### 関連項目
* class [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/)
