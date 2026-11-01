---
title: "PreviewOptions クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "プレビュー生成の要件とストリームデリゲートを設定するオプションを提供します。"
type: docs
url: /ja/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

プレビュー生成の要件とストリームデリゲートを設定するオプションを提供します。

PreviewOptions 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | 使用後に出力ストリームを閉じる新しい PreviewOptions インスタンスを初期化します。 |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | さらに使用できるように出力ストリームをクライアントに返す新しい PreviewOptions インスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | 各レンダリングページの書き込み可能なストリームを取得するために使用されるページストリーム作成デリゲートです。 |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | ページプレビューの高さです。 |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | プレビューを生成するページ番号の配列です。 |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | プレビュー画像の形式です。 |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | ページプレビュー完了デリゲートです。 |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | ページプレビューの幅です。 |

### 例

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # 各ページをレンダリングするための書き込み可能なファイルストリームを提供します
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### Guides
`PreviewOptions` を使用するタスクガイド:

* [Document preview](/watermark/python-net/guides/preview/)

### 関連項目
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
