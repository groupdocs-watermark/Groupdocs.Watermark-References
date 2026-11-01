---
title: "WordProcessingPreviewOptions クラス"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "WordProcessing ドキュメントのプレビュー生成のために要件とストリーム デリゲートを設定するオプションを提供します。"
type: docs
url: /ja/python-net/groupdocs.watermark.options.word_processing/wordprocessingpreviewoptions/
is_root: false
weight: 60
---


## WordProcessingPreviewOptions class

WordProcessing ドキュメントのプレビュー生成のために要件とストリーム デリゲートを設定するオプションを提供します。

WordProcessingPreviewOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingpreviewoptions/__init__/#create_page_stream) | 出力ストリームが閉じられるようにする WordProcessingPreviewOptions の新しいインスタンスを初期化します。 |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingpreviewoptions/__init__/#create_page_stream-release_page_stream) | 出力ストリームがクライアントに返され、さらに使用できるようにする WordProcessingPreviewOptions クラスの新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [resolution](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingpreviewoptions/resolution/) | 生成された画像の解像度（ドット毎インチ）。 |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | 各レンダリングページの書き込み可能なストリームを取得するために使用されるページストリーム作成デリゲートです。(継承元: [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | ページプレビューの高さです。(継承元: [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | プレビューを生成するページ番号の配列です。(継承元: [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | プレビュー画像のフォーマットです。(継承元: [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | ページプレビュー完了デリゲートです。(継承元: [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | ページプレビューの幅です。(継承元: [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [DEFAULT_RESOLUTION](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingpreviewoptions/default_resolution/) | デフォルトの解像度（ドット毎インチ）です。 |

### 関連項目
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
