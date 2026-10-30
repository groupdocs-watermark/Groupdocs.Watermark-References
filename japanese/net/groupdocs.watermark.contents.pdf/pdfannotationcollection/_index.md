---
title: "PdfAnnotationCollection"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "pdf ドキュメント内の注釈のコレクションを表します。"
type: docs
weight: 580
url: /ja/net/groupdocs.watermark.contents.pdf/pdfannotationcollection/
---
## PdfAnnotationCollection class

pdf ドキュメント内の注釈のコレクションを表します。

```csharp
public class PdfAnnotationCollection : RemoveOnlyListBase<PdfAnnotation>
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
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(PdfAnnotation) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(PdfAnnotation) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(PdfAnnotation) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### 備考

このコレクションには [`PdfAnnotation`](../pdfannotation) タイプの項目が含まれています。

### 関連項目

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [PdfAnnotation](../pdfannotation)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
