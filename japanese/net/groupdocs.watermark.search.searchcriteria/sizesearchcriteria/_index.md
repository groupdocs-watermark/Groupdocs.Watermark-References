---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "透かしのサイズでフィルタリングできる基準を表します。"
type: docs
weight: 2730
url: /ja/net/groupdocs.watermark.search.searchcriteria/sizesearchcriteria/
---
## SizeSearchCriteria class

透かしのサイズでフィルタリングできる基準を表します。

```csharp
public class SizeSearchCriteria : SearchCriteria
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SizeSearchCriteria](sizesearchcriteria)(Dimension, double, double) | 指定された次元、開始値、終了値で [`SizeSearchCriteria`](../sizesearchcriteria) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Dimension](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/dimension) { get; } | 検索対象となる透かしの次元を取得します。 |
| [Maximum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/maximum) { get; } | 終了値を取得します。 |
| [Minimum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/minimum) { get; } | 開始値を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | この[`SearchCriteria`](../searchcriteria) を論理 AND 演算子で他の条件と組み合わせます。 |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | この[`SearchCriteria`](../searchcriteria) を否定します。 |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | この[`SearchCriteria`](../searchcriteria) を論理 OR 演算子で他の条件と組み合わせます。 |

### 備考

**Learn more:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### 例

検索条件を使用して透かしを検索し、削除します。

```csharp
using (Watermarker watermarker = new Watermarker(@"C:\test.some_ext"))
{
    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
    TextSearchCriteria textCriteria = new TextSearchCriteria(new Regex("^Test watermark$"));
    PossibleWatermarkCollection watermarks = watermarker.Search(textCriteria.And(widthRange.Or(rotateAngle)));
    watermarks.Clear();
    watermarker.Save();
}
```

### 関連項目

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
