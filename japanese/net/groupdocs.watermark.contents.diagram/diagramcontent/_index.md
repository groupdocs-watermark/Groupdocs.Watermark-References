---
title: "DiagramContent"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "Visio ドキュメントを表します。"
type: docs
weight: 170
url: /ja/net/groupdocs.watermark.contents.diagram/diagramcontent/
---
## DiagramContent class

Visio ドキュメントを表します。

```csharp
public sealed class DiagramContent : Content
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [HeaderFooter](../../groupdocs.watermark.contents.diagram/diagramcontent/headerfooter) { get; } | この[`DiagramContent`](../diagramcontent) のヘッダーとフッターを取得します。 |
| [Pages](../../groupdocs.watermark.contents.diagram/diagramcontent/pages) { get; } | この[`DiagramContent`](../diagramcontent) のすべてのページのコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | 現在のインスタンスを破棄します。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | コンテンツ内のすべての画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 指定された検索条件に従って画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | コンテンツ内のすべての可能な透かしを検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects)で指定されたオブジェクトで実行されます。 |

### 備考

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)
* [Existing objects in diagram document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+diagram+document)

### 関連項目

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Diagram](../../groupdocs.watermark.contents.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
