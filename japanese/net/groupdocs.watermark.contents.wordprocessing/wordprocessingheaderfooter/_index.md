---
title: "WordProcessingHeaderFooter"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "Word 文書のヘッダー/フッターを表します。"
type: docs
weight: 1360
url: /ja/net/groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/
---
## WordProcessingHeaderFooter class

Word 文書のヘッダー/フッターを表します。

```csharp
public class WordProcessingHeaderFooter : ContentPart
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [HeaderFooterType](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/headerfootertype) { get; } | この[`WordProcessingHeaderFooter`](../wordprocessingheaderfooter) のタイプを取得します。 |
| [IsLinkedToPrevious](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/islinkedtoprevious) { get; set; } | このヘッダー/フッターが前のセクションの対応するヘッダー/フッターにリンクされているかどうかを示す値を取得または設定します。 |
| [Section](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfooter/section) { get; } | この[`WordProcessingHeaderFooter`](../wordprocessingheaderfooter) の親セクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | コンテンツ内のすべての画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 指定された検索条件に従って画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | コンテンツ内のすべての可能な透かしを検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects)で指定されたオブジェクトで実行されます。 |

### 関連項目

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
