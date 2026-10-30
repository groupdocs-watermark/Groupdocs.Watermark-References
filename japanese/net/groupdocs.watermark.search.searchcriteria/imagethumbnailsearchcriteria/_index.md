---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "コンテンツ内の画像を検索するための検索基準を表します。"
type: docs
weight: 2650
url: /ja/net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/
---
## ImageThumbnailSearchCriteria class

コンテンツ内の画像を検索するための検索基準を表します。

```csharp
public class ImageThumbnailSearchCriteria : ImageSearchCriteria
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor)(Stream) | 指定されたストリームで、[`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) クラスの新しいインスタンスを初期化します。 |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor_1)(string) | 指定されたファイルパスで、[`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | 画像間の許容最大差異を取得または設定します。 |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | 特定のページ番号のリストを取得または設定します |
| [ThumbnailSize](../../groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/thumbnailsize) { get; set; } | サムネイルサイズを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | この[`SearchCriteria`](../searchcriteria) を論理 AND 演算子で他の条件と組み合わせます。 |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | この[`SearchCriteria`](../searchcriteria) を否定します。 |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | この[`SearchCriteria`](../searchcriteria) を論理 OR 演算子で他の条件と組み合わせます。 |

### 備考

この検索基準は、画像類似度の計算に二値化されたサムネイル画像を使用します。

### 関連項目

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
