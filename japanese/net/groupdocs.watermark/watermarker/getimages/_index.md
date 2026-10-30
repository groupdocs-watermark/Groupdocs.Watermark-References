---
title: "GetImages"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "指定された検索条件に従って画像を検索します。"
type: docs
weight: 80
url: /ja/net/groupdocs.watermark/watermarker/getimages/
---
## GetImages(ImageSearchCriteria) {#getimages_1}

指定された検索条件に従って画像を検索します。

```csharp
public WatermarkableImageCollection GetImages(ImageSearchCriteria searchCriteria)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| searchCriteria | ImageSearchCriteria | 使用する検索条件です。 |

### 戻り値

見つかった画像のコレクションです。

### 備考

検索は [`SearchableObjects`](../searchableobjects) で指定されたオブジェクト内で実行されます。

透かしの検索について詳しくは [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks) をご覧ください。

### 例

サポートされている任意のタイプのドキュメントから、参照と類似したすべての画像を削除します。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
    WatermarkableImageCollection images = watermarker.GetImages(criteria);
    images.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### 関連項目

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [ImageSearchCriteria](../../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## GetImages() {#getimages}

ドキュメント内のすべての画像を検索します。

```csharp
public WatermarkableImageCollection GetImages()
```

### 戻り値

見つかった画像のコレクションです。

### 備考

検索は [`SearchableObjects`](../searchableobjects) で指定されたオブジェクト内で実行されます。

透かしの検索について詳しくは [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks) をご覧ください。

### 例

サポートされている任意のタイプのドキュメント内のすべての画像に透かしを追加します。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // テキストまたは画像の透かしを初期化します。
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // ドキュメント内のすべての画像を検索します。
    WatermarkableImageCollection images = watermarker.GetImages();

    // 透かしを追加します。
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.AddWatermark(watermark);
    }

    // 変更を保存します。
    watermarker.Save(@"D:\output.doc");
}
```

### 関連項目

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
