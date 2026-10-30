---
title: "Remove"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "ドキュメントから透かしを削除します。"
type: docs
weight: 90
url: /ja/net/groupdocs.watermark/watermarker/remove/
---
## Remove(PossibleWatermark) {#remove}

ドキュメントから透かしを削除します。

```csharp
public void Remove(PossibleWatermark possibleWatermark)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| possibleWatermark | PossibleWatermark | 削除する透かしです。 |

### 備考

透かしの削除について詳しくは: [Removing found watermarks](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### 例

任意のサポート対象タイプのドキュメントから、特定のテキストまたは画像を含む最初の可能性のある透かしを検索して削除します。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    if (watermarks.Count > 0)
    {
        watermarker.Remove(watermarks[0]);
    }

    watermarker.Save(@"D:\output.doc");
}
```

### 関連項目

* class [PossibleWatermark](../../../groupdocs.watermark.search/possiblewatermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Remove(PossibleWatermarkCollection) {#remove_1}

コレクション内のすべての透かしをドキュメントから削除します。

```csharp
public void Remove(PossibleWatermarkCollection possibleWatermarks)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| possibleWatermarks | PossibleWatermarkCollection | 削除する透かしのコレクションです。 |

### 備考

透かしの削除について詳しくは [Removing found watermarks](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### 例

サポートされている任意のタイプのドキュメントから、特定のテキストまたは画像を含むすべての可能な透かしを検索して削除します。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarker.Remove(watermarks);
    watermarker.Save(@"D:\output.doc");
}
```

### 関連項目

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
