---
title: "OfficeImageFillFormatTWatermarkableImage"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示任何受支持的办公内容中的图像填充格式设置。"
type: docs
weight: 520
url: /zh/net/groupdocs.watermark.contents/officeimagefillformat-1/
---
## OfficeImageFillFormat&lt;TWatermarkableImage&gt; class

表示任何受支持的办公内容中的图像填充格式设置。

```csharp
public abstract class OfficeImageFillFormat<TWatermarkableImage>
    where TWatermarkableImage : WatermarkableImage
```

| 参数 | 描述 |
| --- | --- |
| TWatermarkableImage | 用于背景的可水印图像的确切类型。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [BackgroundImage](../../groupdocs.watermark.contents/officeimagefillformat-1/backgroundimage) { get; set; } | 获取或设置背景图像。 |
| abstract [TileAsTexture](../../groupdocs.watermark.contents/officeimagefillformat-1/tileastexture) { get; set; } | 获取或设置一个值，指示图像是否在背景上平铺。 |
| abstract [Transparency](../../groupdocs.watermark.contents/officeimagefillformat-1/transparency) { get; set; } | 获取或设置背景图像的透明度，取值范围为 0.0（不透明）至 1.0（完全透明）。 |

### 另请参阅

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Contents](../../groupdocs.watermark.contents)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
