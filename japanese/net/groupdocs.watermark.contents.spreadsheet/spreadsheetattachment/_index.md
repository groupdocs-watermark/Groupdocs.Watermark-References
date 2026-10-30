---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "Excel ドキュメントに添付されたファイルを表します。"
type: docs
weight: 1100
url: /ja/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/
---
## SpreadsheetAttachment class

Excel ドキュメントに添付されたファイルを表します。

```csharp
public class SpreadsheetAttachment : Attachment, ITwoDObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/alternativetext) { get; set; } | 添付ファイルに関連付けられた説明（代替）テキストを取得または設定します。 |
| override [Content](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/content) { get; set; } | 添付ファイルの内容を取得または設定します。 |
| [Height](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/height) { get; set; } | 添付フレームの高さをポイント単位で取得または設定します。 |
| [IsLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/islink) { get; } | コンテンツがファイルへのリンクのみを含むかどうかを示す値を取得します。 |
| [PreviewImageContent](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/previewimagecontent) { get; set; } | 添付ファイルのプレビュー画像をバイト配列として取得または設定します。 |
| [SourceFullName](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/sourcefullname) { get; } | 添付ファイルの完全な名前を取得します。 |
| [Width](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/width) { get; set; } | ポイント単位で添付フレームの幅を取得または設定します。 |
| [X](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/x) { get; set; } | ポイント単位でワークシートの左端から添付フレームの水平オフセットを取得または設定します。 |
| [Y](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/y) { get; set; } | ポイント単位でワークシートの上端から添付フレームの垂直オフセットを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | 添付ファイルからコンテンツを読み込みます。 |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | 指定されたロードオプションを使用して、添付ファイルからコンテンツを読み込みます。 |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | 指定されたロードオプションと設定を使用して、添付ファイルからコンテンツを読み込みます。 |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | 添付ファイルに保存されているドキュメントに関する情報を取得します。 |

### 関連項目

* class [Attachment](../../groupdocs.watermark.common/attachment)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
