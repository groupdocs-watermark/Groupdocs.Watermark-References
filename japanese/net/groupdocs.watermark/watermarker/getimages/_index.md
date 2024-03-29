---
title: GetImages
second_title: GroupDocs.Watermark for .NET API リファレンス
description: 指定した検索条件に従って画像を検索します
type: docs
weight: 80
url: /ja/net/groupdocs.watermark/watermarker/getimages/
---
## GetImages(ImageSearchCriteria) {#getimages_1}

指定した検索条件に従って画像を検索します。

```csharp
public WatermarkableImageCollection GetImages(ImageSearchCriteria searchCriteria)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| searchCriteria | ImageSearchCriteria | 使用する検索条件。 |

### 戻り値

見つかった画像のコレクション。

### 備考

検索は、で指定されたオブジェクトで実行されます[`SearchableObjects`](../searchableobjects).

watermarks の検索の詳細[透かしの検索](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### 例

サポートされているタイプのドキュメントから参照に類似するすべての画像を削除します。

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
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

---

## GetImages() {#getimages}

ドキュメント内のすべての画像を検索します。

```csharp
public WatermarkableImageCollection GetImages()
```

### 戻り値

見つかった画像のコレクション。

### 備考

検索は、で指定されたオブジェクトで実行されます[`SearchableObjects`](../searchableobjects).

watermarks の検索の詳細[透かしの検索](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### 例

サポートされているタイプのドキュメント内のすべての画像に透かしを追加します。

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

    // 変更内容を保存。
    watermarker.Save(@"D:\output.doc");
}
```

### 関連項目

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [Watermarker](../../watermarker)
* 名前空間 [GroupDocs.Watermark](../../watermarker)
* 組み立て [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
