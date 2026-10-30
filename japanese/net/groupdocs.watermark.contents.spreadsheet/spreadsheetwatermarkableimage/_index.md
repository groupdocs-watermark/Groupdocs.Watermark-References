---
title: "SpreadsheetWatermarkableImage"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "Excel ドキュメント内の画像を表します。"
type: docs
weight: 1320
url: /ja/net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/
---
## SpreadsheetWatermarkableImage class

Excel ドキュメント内の画像を表します。

```csharp
public class SpreadsheetWatermarkableImage : WatermarkableImage
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SpreadsheetWatermarkableImage](spreadsheetwatermarkableimage)(byte[]) | 指定された画像データを使用して、[`SpreadsheetWatermarkableImage`](../spreadsheetwatermarkableimage)クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | この [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) の高さ（ピクセル単位）を取得します。 |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | この [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) の幅（ピクセル単位）を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | この [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) に透かしを追加します。このメソッドは、透かしのオフセットとサイズがピクセル単位で測定されていると想定します（割り当てられている場合）。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | コンテンツ内のすべての画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 指定された検索条件に従って画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | 画像をバイト配列として取得します。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | コンテンツ内のすべての可能な透かしを検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects)で指定されたオブジェクトで実行されます。 |

### 関連項目

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
