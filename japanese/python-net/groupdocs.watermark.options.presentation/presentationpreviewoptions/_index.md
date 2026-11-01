---
title: "PresentationPreviewOptions クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "プレゼンテーション ドキュメントのプレビュー生成の要件とストリーム デリゲートを設定するオプションを表します。"
type: docs
url: /ja/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/
is_root: false
weight: 40
---


## PresentationPreviewOptions class

プレゼンテーション ドキュメントのプレビュー生成の要件とストリーム デリゲートを設定するオプションを表します。

PresentationPreviewOptions 型は以下のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/__init__/#create_page_stream) | 出力ストリームを閉じるように、PresentationPreviewOptions クラスの新しいインスタンスを初期化します。 |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/__init__/#create_page_stream-release_page_stream) | 出力ストリームをクライアントに返してさらに使用できるように、[`PresentationPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/) の新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [resolution](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/resolution/) | 生成された画像の解像度（ドット毎インチ）。 |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | 各レンダリングページの書き込み可能なストリームを取得するために使用されるページストリーム作成デリゲートです。(継承元: [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | ページプレビューの高さです。(継承元: [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | プレビューを生成するページ番号の配列です。(継承元: [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | プレビュー画像のフォーマットです。(継承元: [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | ページプレビュー完了デリゲートです。(継承元: [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | ページプレビューの幅です。(継承元: [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [DEFAULT_RESOLUTION](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/default_resolution/) | デフォルトの解像度（ドット毎インチ）です。 |

### 関連項目
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
