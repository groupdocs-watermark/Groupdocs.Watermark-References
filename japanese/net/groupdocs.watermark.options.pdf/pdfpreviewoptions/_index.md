---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "PDFドキュメントのプレビュー生成のための要件とストリームデリゲートを設定するオプションを提供します。"
type: docs
weight: 1960
url: /ja/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/
---
## PdfPreviewOptions class

PDFドキュメントのプレビュー生成のための要件とストリームデリゲートを設定するオプションを提供します。

```csharp
public class PdfPreviewOptions : PreviewOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PdfPreviewOptions](pdfpreviewoptions#constructor)(CreatePageStream) | [`PdfPreviewOptions`](../pdfpreviewoptions) クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。 |
| [PdfPreviewOptions](pdfpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | [`PdfPreviewOptions`](../pdfpreviewoptions) クラスの新しいインスタンスを初期化し、出力ストリームをクライアントに返してさらに使用できるようにします。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | ページストリーム作成デリゲートのインスタンスを取得または設定します。 |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | ページプレビューの高さを取得または設定します。 |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | プレビューを生成するページ番号の配列を取得または設定します。 |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | プレビュー画像の形式を取得または設定します。 |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | ページプレビュー完了デリゲートのインスタンスを取得または設定します。 |
| [Resolution](../../groupdocs.watermark.options.pdf/pdfpreviewoptions/resolution) { get; set; } | 生成された画像の解像度（dpi）を取得または設定します。 |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | ページプレビューの幅を取得または設定します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.pdf/pdfpreviewoptions/defaultresolution) | デフォルトの解像度（dpi）。 |

### 関連項目

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
