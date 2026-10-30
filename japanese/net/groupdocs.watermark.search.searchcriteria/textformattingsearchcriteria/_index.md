---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "テキスト書式設定でフィルタリングできる基準を表します。"
type: docs
weight: 2740
url: /ja/net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/
---
## TextFormattingSearchCriteria class

テキスト書式設定でフィルタリングできる基準を表します。

```csharp
public class TextFormattingSearchCriteria : SearchCriteria
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TextFormattingSearchCriteria](textformattingsearchcriteria)() | [`TextFormattingSearchCriteria`](../textformattingsearchcriteria) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/backgroundcolorrange) { get; set; } | テキスト背景色で透かしをフィルタリングするために使用される色の範囲を取得または設定します。 |
| [FontBold](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontbold) { get; set; } | 透かしテキストの書式設定で使用されるフォントが太字かどうかを示す値を取得または設定します。 |
| [FontItalic](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontitalic) { get; set; } | 透かしテキストの書式設定で使用されるフォントが斜体かどうかを示す値を取得または設定します。 |
| [FontName](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontname) { get; set; } | 可能な透かしテキスト書式設定で使用されるフォントの名前を取得または設定します。 |
| [FontStrikeout](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontstrikeout) { get; set; } | 透かしテキスト書式設定で使用されるフォントが取り消し線かどうかを示す値を取得または設定します。 |
| [FontUnderline](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontunderline) { get; set; } | 透かしテキスト書式設定で使用されるフォントが下線かどうかを示す値を取得または設定します。 |
| [ForegroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/foregroundcolorrange) { get; set; } | テキスト前景色で透かしをフィルタリングするために使用される色の範囲を取得または設定します。 |
| [MaxFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/maxfontsize) { get; set; } | フォントサイズの終了値を取得または設定します。 |
| [MinFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/minfontsize) { get; set; } | フォントサイズの開始値を取得または設定します。 |

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

特定のテキスト書式設定を持つ可能性のある透かしを削除します（ドキュメントタイプに関係なく）。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.doc"))
{
    TextFormattingSearchCriteria criteria = new TextFormattingSearchCriteria();
    criteria.ForegroundColorRange = new ColorRange();
    criteria.ForegroundColorRange.MinHue = -5;
    criteria.ForegroundColorRange.MaxHue = 10;
    criteria.ForegroundColorRange.MinBrightness = 0.01f;
    criteria.ForegroundColorRange.MaxBrightness = 0.99f;
    criteria.BackgroundColorRange = new ColorRange();
    criteria.BackgroundColorRange.IsEmpty = true;
    criteria.FontName = "Arial";
    criteria.MinFontSize = 19;
    criteria.MaxFontSize = 42;
    criteria.FontBold = true;

    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    watermarks.Clear();
    watermarker.Save();
}
```

### 関連項目

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
