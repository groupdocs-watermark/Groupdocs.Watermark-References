---
title: "PdfAnnotationWatermarkOptions クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "PDF ドキュメントに注釈透かしを追加する際の透かし追加オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
is_root: false
weight: 10
---


## PdfAnnotationWatermarkOptions class

PDF ドキュメントに注釈透かしを追加する際の透かし追加オプションを表します。

詳しくは:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

PdfAnnotationWatermarkOptions 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/__init__/) | 新しい [`PdfAnnotationWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/) クラスのインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/page_index/) | 透かしを追加するページインデックスです。 |
| [print_only](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/print_only/) | 注釈が印刷はされるが、PDF ビューアアプリケーションでは表示されないかどうかを示す値です。 |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | クラスのデフォルト値を取得します。（[`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) から継承） |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfAnnotationWatermarkOptions

def add_annotation_image_watermark():
    load_options = PdfLoadOptions()
    with Watermarker("./test.pdf", load_options) as watermarker:
        with ImageWatermark("./icon.png") as watermark:
            options = PdfAnnotationWatermarkOptions()
            # PageIndex = -1 はすべてのページに透かしを適用します（デフォルト）
            watermarker.add(watermark, options)
        watermarker.save("./output.pdf")
```

### 関連項目
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
