---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "プレビュー生成のための要件設定とストリームデリゲートのオプションを提供します。"
type: docs
weight: 2140
url: /ja/net/groupdocs.watermark.options/previewoptions/
---
## PreviewOptions class

プレビュー生成のための要件設定とストリームデリゲートのオプションを提供します。

```csharp
public class PreviewOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream) | 出力ストリームが閉じられるように、[`PreviewOptions`](../previewoptions) クラスの新しいインスタンスを初期化します。 |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | 出力ストリームがクライアントに返され、さらに使用できるように、[`PreviewOptions`](../previewoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | ページストリーム作成デリゲートのインスタンスを取得または設定します。 |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | ページプレビューの高さを取得または設定します。 |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | プレビューを生成するページ番号の配列を取得または設定します。 |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | プレビュー画像の形式を取得または設定します。 |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | ページプレビュー完了デリゲートのインスタンスを取得または設定します。 |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | ページプレビューの幅を取得または設定します。 |

### 関連項目

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
