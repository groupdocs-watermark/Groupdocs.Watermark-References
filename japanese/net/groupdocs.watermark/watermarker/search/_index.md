---
title: "Search"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "ドキュメント内のすべての可能な透かしを検索します。"
type: docs
weight: 110
url: /ja/net/groupdocs.watermark/watermarker/search/
---
## Search() {#search}

ドキュメント内のすべての可能な透かしを検索します。

```csharp
public PossibleWatermarkCollection Search()
```

### 戻り値

可能な透かしのコレクションです。

### 備考

検索は [`SearchableObjects`](../searchableobjects) で指定されたオブジェクト内で実行されます。

透かしの検索について詳しくは [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks) をご覧ください。

### 例

サポートされている任意のタイプのドキュメント内の可能な透かしをカウントします。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    PossibleWatermarkCollection watermarks = watermarker.Search();
    Console.WrileLine(watermarks.Count);
}
```

### 関連項目

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Search(SearchCriteria) {#search_1}

指定された検索基準に従って、可能な透かしを検索します。

```csharp
public PossibleWatermarkCollection Search(SearchCriteria searchCriteria)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| searchCriteria | SearchCriteria | 使用する検索条件です。 |

### 戻り値

可能な透かしのコレクションです。

### 備考

検索は [`SearchableObjects`](../searchableobjects) で指定されたオブジェクト内で実行されます。

透かしの検索について詳しくは [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks) をご覧ください。

### 例

サポートされている任意のタイプのドキュメントから、特定のテキストまたは画像を含むすべての可能な透かしを検索して削除します。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarks.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### 関連項目

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [SearchCriteria](../../../groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
