---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示在多帧图像中添加水印时的水印添加选项。"
type: docs
weight: 1870
url: /zh/net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
---
## MultiframeImageWatermarkOptions class

表示在向多帧图像添加水印时的水印添加选项。

```csharp
public class MultiframeImageWatermarkOptions : WatermarkOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor)() | 初始化 [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions) 类的新实例。 |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor_1)(int) | 使用指定的帧索引初始化 [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | 获取或设置用于添加水印的帧索引。 |

### 备注

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### 示例

向多帧图像的特定帧添加水印。

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

### 另请参阅

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
