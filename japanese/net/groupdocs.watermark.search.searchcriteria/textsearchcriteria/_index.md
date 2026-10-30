---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "透かしテキストでフィルタリングできる基準を表します。"
type: docs
weight: 2750
url: /ja/net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/
---
## TextSearchCriteria class

透かしテキストでフィルタリングできる基準を表します。

```csharp
public class TextSearchCriteria : PageSearchCriteria
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TextSearchCriteria](textsearchcriteria#constructor_2)(Regex) | 指定された正規表現で、[`TextSearchCriteria`](../textsearchcriteria) クラスの新しいインスタンスを初期化します。 |
| [TextSearchCriteria](textsearchcriteria#constructor)(string) | 検索文字列を使用して、[`TextSearchCriteria`](../textsearchcriteria) クラスの新しいインスタンスを初期化します。 |
| [TextSearchCriteria](textsearchcriteria#constructor_1)(string, bool) | 検索文字列と比較用フラグを指定して、[`TextSearchCriteria`](../textsearchcriteria) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | 特定のページ番号のリストを取得または設定します |
| [Pattern](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/pattern) { get; } | 検索パターンを取得します。 |
| [SkipUnreadableCharacters](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/skipunreadablecharacters) { get; set; } | 文字列比較時に読めない文字をスキップするかどうかを示す値を取得または設定します。 |

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

* class [PageSearchCriteria](../pagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
