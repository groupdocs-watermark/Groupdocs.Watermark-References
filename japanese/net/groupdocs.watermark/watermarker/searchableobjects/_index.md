---
title: "SearchableObjects"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "透かし検索に含めるコンテンツオブジェクトを取得または設定します。"
type: docs
weight: 20
url: /ja/net/groupdocs.watermark/watermarker/searchableobjects/
---
## Watermarker.SearchableObjects property

透かし検索に含めるコンテンツオブジェクトを取得または設定します。

```csharp
public SearchableObjects SearchableObjects { get; set; }
```

### Property Value

透かし検索に含めるオブジェクトです。

### 備考

このプロパティは、画像検索で使用されるコンテンツオブジェクトも指定します。詳細については[`Search`](../search)および[`GetImages`](../getimages)メソッドをご覧ください。

透かしの検索について詳しくは: [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### 例

PDFドキュメントからすべてのXObjectsとArtifactsを削除します。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf"))
{
    // XObjectsとArtifactsのみを検索対象とすることを指定します。
    watermarker.SearchableObjects.PdfSearchableObjects
        = PdfSearchableObjects.XObjects | PdfSearchableObjects.Artifacts; 

    PossibleWatermarkCollection watermarks = watermarker.Search();

    // 見つかったすべてのオブジェクトを削除します。
    watermarks.Clear();

    // 変更を保存します。
    watermarker.Save();
}
```

### 関連項目

* class [SearchableObjects](../../../groupdocs.watermark.search.objects/searchableobjects)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
