---
title: "SpreadsheetWorksheet"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "Excel ドキュメントのワークシートを表します。"
type: docs
weight: 1330
url: /ja/net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/
---
## SpreadsheetWorksheet class

Excel ドキュメントのワークシートを表します。

```csharp
public class SpreadsheetWorksheet : ContentPart
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/attachments) { get; } | この[`SpreadsheetWorksheet`](../spreadsheetworksheet)のすべての添付ファイルのコレクションを取得します。 |
| [BackgroundImage](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/backgroundimage) { get; set; } | この[`SpreadsheetWorksheet`](../spreadsheetworksheet)の背景画像を取得または設定します。 |
| [Charts](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/charts) { get; } | この[`SpreadsheetWorksheet`](../spreadsheetworksheet)のすべてのチャートのコレクションを取得します。 |
| [ContentAreaHeight](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/contentareaheight) { get; } | コンテンツ領域の高さ（ポイント単位）を取得します。 |
| [ContentAreaHeightPx](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/contentareaheightpx) { get; } | コンテンツ領域の高さ（ピクセル単位）を取得します。 |
| [ContentAreaWidth](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/contentareawidth) { get; } | コンテンツ領域の幅（ポイント単位）を取得します。 |
| [ContentAreaWidthPx](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/contentareawidthpx) { get; } | コンテンツ領域の幅（ピクセル単位）を取得します。 |
| [HeadersFooters](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/headersfooters) { get; } | ワークシートのヘッダーとフッターのコレクションを取得します。 |
| [PageSetup](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/pagesetup) { get; } | この[`SpreadsheetWorksheet`](../spreadsheetworksheet)の印刷ページ設定を取得します。 |
| [Shapes](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/shapes) { get; } | この[`SpreadsheetWorksheet`](../spreadsheetworksheet)のすべてのシェイプのコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | コンテンツ内のすべての画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 指定された検索条件に従って画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [GetColumnWidth](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/getcolumnwidth)(int) | 指定された列の幅（ポイント単位）を取得します。 |
| [GetColumnWidthPx](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/getcolumnwidthpx)(int) | 指定された列の幅（ピクセル単位）を取得します。 |
| [GetRowHeight](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/getrowheight)(int) | 指定された行の高さ（ポイント単位）を取得します。 |
| [GetRowHeightPx](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/getrowheightpx)(int) | 指定された行の高さ（ピクセル単位）を取得します。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | コンテンツ内のすべての可能な透かしを検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects)で指定されたオブジェクトで実行されます。 |

### 関連項目

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
