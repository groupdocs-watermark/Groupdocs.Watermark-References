---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "スプレッドシート文書のプレビュー生成の要件とストリームデリゲートを設定するオプションを提供します。"
type: docs
weight: 2220
url: /ja/net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/
---
## SpreadsheetPreviewOptions class

スプレッドシート文書のプレビュー生成の要件とストリームデリゲートを設定するオプションを提供します。

```csharp
public class SpreadsheetPreviewOptions : PreviewOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SpreadsheetPreviewOptions](spreadsheetpreviewoptions#constructor)(CreatePageStream) | 出力ストリームが閉じられるように、[`SpreadsheetPreviewOptions`](../spreadsheetpreviewoptions) クラスの新しいインスタンスを初期化します。 |
| [SpreadsheetPreviewOptions](spreadsheetpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | 出力ストリームがクライアントに返され、さらに使用できるように、[`SpreadsheetPreviewOptions`](../spreadsheetpreviewoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | ページストリーム作成デリゲートのインスタンスを取得または設定します。 |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | ページプレビューの高さを取得または設定します。 |
| [OnlyDataArea](../../groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/onlydataarea) { get; set; } | ヘッダー、フッター、余白を除き、データ領域のみをレンダリングするフラグを取得または設定します。 |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | プレビューを生成するページ番号の配列を取得または設定します。 |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | プレビュー画像の形式を取得または設定します。 |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | ページプレビュー完了デリゲートのインスタンスを取得または設定します。 |
| [Resolution](../../groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/resolution) { get; set; } | 生成された画像の解像度（dpi）を取得または設定します。 |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | ページプレビューの幅を取得または設定します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/defaultresolution) | デフォルトの解像度（dpi）。 |

### 関連項目

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
