---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "GIF 画像に透かしを追加する際の透かし追加オプションを表します。"
type: docs
weight: 1830
url: /ja/net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
---
## GifImageWatermarkOptions class

GIF 画像に透かしを追加する際の透かし追加オプションを表します。

```csharp
public sealed class GifImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor)() | [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) クラスの新しいインスタンスを初期化します。 |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor_1)(int) | [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) クラスの新しいインスタンスを、指定されたフレームのインデックスで初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | 透かしを追加するフレームのインデックスを取得または設定します。 |

### 備考

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### 例

GIF画像の特定のフレームに透かしを追加します。

```csharp
GifImageLoadOptions loadOptions = new GifImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 関連項目

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
