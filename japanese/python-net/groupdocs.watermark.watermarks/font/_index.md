---
title: "Font クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "フォントを表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

フォントを表します。

Font 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | 指定されたフォントファミリ名とサイズで新しい Font インスタンスを初期化します。 |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | 指定されたフォントファミリ名、サイズ、スタイルで新しい Font インスタンスを初期化します。 |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | カスタムフォントファミリ名、TrueType フォントを含むフォルダー、サイズ、スタイルで新しい Font インスタンスを初期化します。 |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | カスタムフォントファミリ名、TrueType フォントファイルを含むフォルダー、サイズで新しい Font インスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | フォントは太字です。 |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | この Font のファミリ名です。 |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | TrueType フォントファイルを含むフォルダーです。 |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | フォントは斜体です。 |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | この Font のサイズです。 |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | フォントはテキストに横線を指定します。 |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | この Font のスタイル情報です。 |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | フォントは下線付きです。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Guides
`Font` を使用するタスク ガイド:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### 関連項目
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
