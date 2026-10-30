---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "メールドキュメントのプレビュー生成のための要件設定とストリームデリゲートのオプションを提供します。"
type: docs
weight: 1780
url: /ja/net/groupdocs.watermark.options.email/emailpreviewoptions/
---
## EmailPreviewOptions class

メールドキュメントのプレビュー生成のための要件設定とストリームデリゲートのオプションを提供します。

```csharp
public class EmailPreviewOptions : PreviewOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [EmailPreviewOptions](emailpreviewoptions#constructor)(CreatePageStream) | [`EmailPreviewOptions`](../emailpreviewoptions) クラスの新しいインスタンスを初期化し、出力ストリームを閉じます。 |
| [EmailPreviewOptions](emailpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | [`EmailPreviewOptions`](../emailpreviewoptions) クラスの新しいインスタンスを初期化し、出力ストリームをクライアントに返してさらに使用できるようにします。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | ページストリーム作成デリゲートのインスタンスを取得または設定します。 |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | ページプレビューの高さを取得または設定します。 |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | プレビューを生成するページ番号の配列を取得または設定します。 |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | プレビュー画像の形式を取得または設定します。 |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | ページプレビュー完了デリゲートのインスタンスを取得または設定します。 |
| [Resolution](../../groupdocs.watermark.options.email/emailpreviewoptions/resolution) { get; set; } | 生成された画像の解像度（dpi）を取得または設定します。 |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | ページプレビューの幅を取得または設定します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.email/emailpreviewoptions/defaultresolution) | デフォルトの解像度（dpi）。 |

### 関連項目

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
