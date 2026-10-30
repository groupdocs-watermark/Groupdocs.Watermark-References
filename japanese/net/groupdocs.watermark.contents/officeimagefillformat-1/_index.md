---
title: "OfficeImageFillFormatTWatermarkableImage"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "サポートされているすべてのオフィス コンテンツにおける画像塗りつぶし形式設定を表します。"
type: docs
weight: 520
url: /ja/net/groupdocs.watermark.contents/officeimagefillformat-1/
---
## OfficeImageFillFormat&lt;TWatermarkableImage&gt; class

サポートされているすべてのオフィス コンテンツにおける画像塗りつぶし形式設定を表します。

```csharp
public abstract class OfficeImageFillFormat<TWatermarkableImage>
    where TWatermarkableImage : WatermarkableImage
```

| パラメーター | 説明 |
| --- | --- |
| TWatermarkableImage | 背景として使用される透かし可能画像の正確なタイプ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| abstract [BackgroundImage](../../groupdocs.watermark.contents/officeimagefillformat-1/backgroundimage) { get; set; } | 背景画像を取得または設定します。 |
| abstract [TileAsTexture](../../groupdocs.watermark.contents/officeimagefillformat-1/tileastexture) { get; set; } | 画像が背景全体にタイル状に配置されているかどうかを示す値を取得または設定します。 |
| abstract [Transparency](../../groupdocs.watermark.contents/officeimagefillformat-1/transparency) { get; set; } | 背景画像の透明度を 0.0（不透明）から 1.0（完全に透明）までの値として取得または設定します。 |

### 関連項目

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Contents](../../groupdocs.watermark.contents)
* assembly [GroupDocs.Watermark](../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
