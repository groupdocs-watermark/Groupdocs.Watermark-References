---
title: "PdfArtifactCollection"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "pdf コンテンツ内のアーティファクトのコレクションを表します。"
type: docs
weight: 610
url: /ja/net/groupdocs.watermark.contents.pdf/pdfartifactcollection/
---
## PdfArtifactCollection class

pdf コンテンツ内のアーティファクトのコレクションを表します。

```csharp
public class PdfArtifactCollection : RemoveOnlyListBase<PdfArtifact>
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
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(PdfArtifact) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(PdfArtifact) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(PdfArtifact) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### 備考

このコレクションは [`PdfArtifact`](../pdfartifact) 型の項目を含みます。

### 関連項目

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [PdfArtifact](../pdfartifact)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
