---
title: "ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "ドキュメント内の画像を検索するための検索基準を表します。"
type: docs
weight: 2630
url: /ja/net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/
---
## ImageDctHashSearchCriteria class

ドキュメント内の画像を検索するための検索基準を表します。

```csharp
public class ImageDctHashSearchCriteria : ImageSearchCriteria
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor)(Stream) | 指定されたストリームで新しい [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) クラスのインスタンスを初期化します。 |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor_1)(string) | 指定されたファイルパスで新しい [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) クラスのインスタンスを初期化します。 |

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

### 備考

この検索基準は、画像の類似性を計算するために DCT ベースの知覚的画像ハッシュを使用します。 **詳細を見る:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### 例

添付ファイル（pdf）内の画像を検索します。

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    PdfSearchableObjects = PdfSearchableObjects.All
};
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions, settings))
{
    // ドキュメント画像と比較するサンプル画像を指定します
    ImageSearchCriteria criteria = new ImageDctHashSearchCriteria(@"D:\sample.png");
    // 類似画像を検索します
    PossibleWatermarkCollection possibleWatermarks = watermarker.Search(criteria);
    // 見つかった画像の透かしを削除または変更する
    // ...
}
```

### 関連項目

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
