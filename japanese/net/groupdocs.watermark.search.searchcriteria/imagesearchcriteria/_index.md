---
title: "ImageSearchCriteria"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "画像検索基準の基底クラスを提供します。"
type: docs
weight: 2640
url: /ja/net/groupdocs.watermark.search.searchcriteria/imagesearchcriteria/
---
## ImageSearchCriteria class

画像検索基準の基底クラスを提供します。

```csharp
public abstract class ImageSearchCriteria : PageSearchCriteria
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | 画像間の許容最大差異を取得または設定します。 |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | 特定のページ番号のリストを取得または設定します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | この[`SearchCriteria`](../searchcriteria) を論理 AND 演算子で他の条件と組み合わせます。 |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | この[`SearchCriteria`](../searchcriteria) を否定します。 |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | この[`SearchCriteria`](../searchcriteria) を論理 OR 演算子で他の条件と組み合わせます。 |

### 関連項目

* class [PageSearchCriteria](../pagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
