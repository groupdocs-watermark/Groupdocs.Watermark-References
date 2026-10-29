---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示向 GIF 图像添加水印时的水印添加选项。"
type: docs
weight: 1830
url: /zh/net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
---
## GifImageWatermarkOptions class

表示向 GIF 图像添加水印时的水印添加选项。

```csharp
public sealed class GifImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor)() | 初始化 [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) 类的新实例。 |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor_1)(int) | 使用指定的帧索引初始化 [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | 获取或设置用于添加水印的帧索引。 |

### 备注

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### 示例

向 GIF 图像的特定帧添加水印。

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

### 另请参阅

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
