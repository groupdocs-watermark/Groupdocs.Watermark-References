---
title: "GifImageContent"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "透かしを配置できる GIF 画像を表します。"
type: docs
weight: 390
url: /ja/net/groupdocs.watermark.contents.image/gifimagecontent/
---
## GifImageContent class

透かしを配置できる GIF 画像を表します。

```csharp
public sealed class GifImageContent : MultiframeImageContent
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Frames](../../groupdocs.watermark.contents.image/multiframeimagecontent/frames) { get; } | 画像のすべてのフレームのコレクションを取得します。 |
| virtual [Height](../../groupdocs.watermark.contents.image/imagecontent/height) { get; } | この[`ImageContent`](../imagecontent)の高さ（ピクセル単位）を取得します。 |
| virtual [Width](../../groupdocs.watermark.contents.image/imagecontent/width) { get; } | この[`ImageContent`](../imagecontent)の幅（ピクセル単位）を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | 現在のインスタンスを破棄します。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | コンテンツ内のすべての画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 指定された検索条件に従って画像を検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | コンテンツ内のすべての可能な透かしを検索します。検索は [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) で指定されたオブジェクトで実行されます。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 指定された検索条件に従って可能性のある透かしを検索します。検索は[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects)で指定されたオブジェクトで実行されます。 |

### 関連項目

* class [MultiframeImageContent](../multiframeimagecontent)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
