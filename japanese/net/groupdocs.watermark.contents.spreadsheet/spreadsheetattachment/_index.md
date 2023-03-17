---
title: SpreadsheetAttachment
second_title: GroupDocs.Watermark for .NET API リファレンス
description: Excel ドキュメントに添付されたファイルを表します
type: docs
weight: 1030
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
| [AlternativeText](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/alternativetext) { get; set; } | 添付ファイルに関連付けられた説明 (代替) テキストを取得または設定します。 |
| override [Content](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/content) { get; set; } | 添付ファイルの内容を取得または設定します。 |
| [Height](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/height) { get; set; } | アタッチメント フレームの高さをポイント単位で取得または設定します。 |
| [IsLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/islink) { get; } | コンテンツにファイルへのリンクのみが含まれているかどうかを示す値を取得します。 |
| [PreviewImageContent](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/previewimagecontent) { get; set; } | 添付ファイルのプレビュー イメージをバイト配列として取得または設定します。 |
| [SourceFullName](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/sourcefullname) { get; } | 添付ファイルのフルネームを取得します。 |
| [Width](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/width) { get; set; } | アタッチメント フレームの幅をポイント単位で取得または設定します。 |
| [X](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/x) { get; set; } | ワークシートの左境界線からのアタッチメント フレームの水平オフセットをポイント単位で取得または設定します。 |
| [Y](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/y) { get; set; } | ワークシートの上部境界線からの添付フレームの垂直オフセットをポイント単位で取得または設定します. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | 添付ファイルからコンテンツを読み込みます。 |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | 指定されたロード オプションを使用して、添付ファイルからコンテンツをロードします。 |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | 指定されたロード オプションと設定を使用して、添付ファイルからコンテンツをロードします。 |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | 添付ファイルに格納されているドキュメントに関する情報を取得します。 |

### 関連項目

* class [Attachment](../../groupdocs.watermark.common/attachment)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* 名前空間 [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* 組み立て [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->