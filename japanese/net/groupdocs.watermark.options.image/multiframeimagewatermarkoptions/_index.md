---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "マルチフレーム画像に透かしを追加する際の透かし追加オプションを表します。"
type: docs
weight: 1870
url: /ja/net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
---
## MultiframeImageWatermarkOptions class

マルチフレーム画像に透かしを追加する際の透かし追加オプションを表します。

```csharp
public class MultiframeImageWatermarkOptions : WatermarkOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor)() | [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions) クラスの新しいインスタンスを初期化します。 |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor_1)(int) | 指定されたフレームインデックスで [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | 透かしを追加するフレームのインデックスを取得または設定します。 |

### 備考

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### 例

マルチフレーム画像の特定のフレームに透かしを追加します。

```csharp
ImageLoadOptions loadOptions = new ImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 関連項目

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
