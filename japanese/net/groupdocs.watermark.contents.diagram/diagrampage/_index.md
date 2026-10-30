---
title: "DiagramPage"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "Visio ドキュメントのページを表します。"
type: docs
weight: 240
url: /ja/net/groupdocs.watermark.contents.diagram/diagrampage/
---
## DiagramPage class

Visio ドキュメントのページを表します。

```csharp
public class DiagramPage : ContentPart
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundPage](../../groupdocs.watermark.contents.diagram/diagrampage/backgroundpage) { get; } | この [`DiagramPage`](../diagrampage) の背景ページを取得します。 |
| [BottomMargin](../../groupdocs.watermark.contents.diagram/diagrampage/bottommargin) { get; } | 下余白のサイズをポイント単位で取得します。 |
| [Height](../../groupdocs.watermark.contents.diagram/diagrampage/height) { get; } | この [`DiagramPage`](../diagrampage) の高さ（ポイント単位）を取得します。 |
| [IsBackground](../../groupdocs.watermark.contents.diagram/diagrampage/isbackground) { get; } | ページが背景ページかどうかを示す値を取得します。 |
| [IsVisible](../../groupdocs.watermark.contents.diagram/diagrampage/isvisible) { get; set; } | ページが UI に表示されるかどうかを示す値を取得または設定します。 |
| [LeftMargin](../../groupdocs.watermark.contents.diagram/diagrampage/leftmargin) { get; } | 左余白のサイズをポイント単位で取得します。 |
| [Name](../../groupdocs.watermark.contents.diagram/diagrampage/name) { get; } | この [`DiagramPage`](../diagrampage) の名前を取得します。 |
| [RightMargin](../../groupdocs.watermark.contents.diagram/diagrampage/rightmargin) { get; } | 右余白のサイズをポイント単位で取得します。 |
| [Shapes](../../groupdocs.watermark.contents.diagram/diagrampage/shapes) { get; } | ページ上のすべてのシェイプのコレクションを取得します。 |
| [TopMargin](../../groupdocs.watermark.contents.diagram/diagrampage/topmargin) { get; } | 上余白のサイズをポイント単位で取得します。 |
| [Width](../../groupdocs.watermark.contents.diagram/diagrampage/width) { get; } | この [`DiagramPage`](../diagrampage) の幅（ポイント単位）を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | コンテンツ内のすべての画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 指定された検索条件に従って画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | コンテンツ内のすべての可能な透かしを検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects)で指定されたオブジェクトで実行されます。 |

### 関連項目

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Diagram](../../groupdocs.watermark.contents.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
