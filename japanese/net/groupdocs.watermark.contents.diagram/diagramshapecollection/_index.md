---
title: "DiagramShapeCollection"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "Visio ドキュメント内の描画シェイプのコレクションを表します。"
type: docs
weight: 270
url: /ja/net/groupdocs.watermark.contents.diagram/diagramshapecollection/
---
## DiagramShapeCollection class

Visio ドキュメント内の描画シェイプのコレクションを表します。

```csharp
public class DiagramShapeCollection : RemoveOnlyListBase<DiagramShape>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | コレクションに含まれる要素数を取得します。 |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | コレクション内の指定インデックスにある要素を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(DiagramShape) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(DiagramShape) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(DiagramShape) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### 備考

このコレクションには [`DiagramShape`](../diagramshape) 型の項目が含まれます。

### 関連項目

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [DiagramShape](../diagramshape)
* namespace [GroupDocs.Watermark.Contents.Diagram](../../groupdocs.watermark.contents.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
