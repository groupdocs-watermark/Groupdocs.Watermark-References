---
title: "PdfPage"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "pdf ドキュメントのページを表します。"
type: docs
weight: 730
url: /ja/net/groupdocs.watermark.contents.pdf/pdfpage/
---
## PdfPage class

pdf ドキュメントのページを表します。

```csharp
public class PdfPage : ContentPart
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Annotations](../../groupdocs.watermark.contents.pdf/pdfpage/annotations) { get; } | この[`PdfPage`](../pdfpage) のすべての注釈のコレクションを取得します。 |
| [Artifacts](../../groupdocs.watermark.contents.pdf/pdfpage/artifacts) { get; } | この[`PdfPage`](../pdfpage) のすべてのアーティファクトのコレクションを取得します。 |
| [Height](../../groupdocs.watermark.contents.pdf/pdfpage/height) { get; } | この[`PdfPage`](../pdfpage) の高さ（ポイント単位）を取得します。 |
| [Width](../../groupdocs.watermark.contents.pdf/pdfpage/width) { get; } | この[`PdfPage`](../pdfpage) の幅（ポイント単位）を取得します。 |
| [XObjects](../../groupdocs.watermark.contents.pdf/pdfpage/xobjects) { get; } | この[`PdfPage`](../pdfpage) のすべての XObject のコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | コンテンツ内のすべての画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 指定された検索条件に従って画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| virtual [Rasterize](../../groupdocs.watermark.contents.pdf/pdfpage/rasterize)(int, int, PdfImageConversionFormat) | ページコンテンツを画像に変換します。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | コンテンツ内のすべての可能な透かしを検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects)で指定されたオブジェクトで実行されます。 |

### 関連項目

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
