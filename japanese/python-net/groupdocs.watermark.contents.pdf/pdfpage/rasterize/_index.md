---
title: "rasterize メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "ページコンテンツを画像に変換します。"
type: docs
url: /ja/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

ページコンテンツを画像に変換します。

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
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # 最初のページを 100 DPI の PNG 画像にラスタライズする
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### 関連項目
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
