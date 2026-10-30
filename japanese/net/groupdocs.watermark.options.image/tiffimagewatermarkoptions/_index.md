---
title: "TiffImageWatermarkOptions"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "TIFF画像に透かしを追加する際の透かし追加オプションを表します。"
type: docs
weight: 1900
url: /ja/net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
---
## TiffImageWatermarkOptions class

TIFF画像に透かしを追加する際の透かし追加オプションを表します。

```csharp
public sealed class TiffImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor)() | [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) クラスの新しいインスタンスを初期化します。 |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor_1)(int) | 指定されたフレームインデックスで、[`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | 透かしを追加するフレームのインデックスを取得または設定します。 |

### 備考

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### 例

TIFF 画像の特定のフレームに透かしを追加します。

```csharp
TiffImageLoadOptions loadOptions = new TiffImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.tiff", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    TiffImageWatermarkOptions options = new TiffImageWatermarkOptions();
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
