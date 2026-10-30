---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "ドキュメント内の画像を表します。"
type: docs
weight: 470
url: /ja/net/groupdocs.watermark.contents.image/watermarkableimage/
---
## WatermarkableImage class

ドキュメント内の画像を表します。

```csharp
public abstract class WatermarkableImage : ContentPart
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | この[`WatermarkableImage`](../watermarkableimage)の高さ（ピクセル単位）を取得します。 |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | この[`WatermarkableImage`](../watermarkableimage)の幅（ピクセル単位）を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | この[`WatermarkableImage`](../watermarkableimage)に透かしを追加します。このメソッドは、透かしのオフセットとサイズがピクセル単位で測定されていると想定します（割り当てられている場合）。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | コンテンツ内のすべての画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 指定された検索条件に従って画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | 画像をバイト配列として取得します。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | コンテンツ内のすべての可能な透かしを検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects)で指定されたオブジェクトで実行されます。 |

### 備考

**Learn more:**

* [Adding watermark to images inside a document](https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

### 例

サポートされている任意のタイプのドキュメント内のすべての画像に透かしを追加します。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // テキストまたは画像の透かしを初期化します。
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // コンテンツ内のすべての画像を検索します。
    WatermarkableImageCollection images = watermarker.GetImages();

    // 透かしを追加します。
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.Add(watermark);
    }

    // 変更を保存します。
    watermarker.Save(@"D:\output.doc");
}
```

### 関連項目

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
