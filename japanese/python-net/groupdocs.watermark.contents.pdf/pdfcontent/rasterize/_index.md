---
title: "rasterize メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "すべてのコンテンツページを画像に変換します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

すべてのコンテンツページを画像に変換します。

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| horizontal_resolution | `int` | 水平画像解像度。 |
| vertical_resolution | `int` | 垂直画像解像度。 |
| image_format | `PdfImageConversionFormat` | 画像形式。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # 透かしを追加（オプション）
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # すべてのページを 100x100 DPI でラスタライズし、PNG 画像に変換する
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### 関連項目
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
