---
title: "ImageWatermark"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示图像水印。"
type: docs
weight: 3190
url: /zh/net/groupdocs.watermark.watermarks/imagewatermark/
---
## ImageWatermark class

表示图像水印。

```csharp
public sealed class ImageWatermark : Watermark, IDisposable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageWatermark](imagewatermark#constructor)(Stream) | 使用指定的流初始化 [`ImageWatermark`](../imagewatermark) 类的新实例。 |
| [ImageWatermark](imagewatermark#constructor_1)(string) | 使用指定的文件路径初始化 [`ImageWatermark`](../imagewatermark) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | 获取或设置一个值，指示是否在计算水印大小和坐标时考虑父级边距。 |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的期望高度。 |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的水平对齐方式。 |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | 获取或设置一个值，指示是否应将水印放置在背景中。 |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的边距设置。 |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的不透明度。 |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的页面设置。 |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的旋转角度（以度为单位）。 |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | 获取或设置一个值，指示是否在文档元数据中保存已添加水印的信息。 |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | 获取或设置一个值，定义水印大小如何依赖于父级大小。 |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | 获取或设置一个值，指定水印的尺寸方式。 |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | 获取或设置用于定义重复水印的选项 |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的垂直对齐方式。 |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的期望宽度。 |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的 X 坐标。 |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的 Y 坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../groupdocs.watermark.watermarks/imagewatermark/dispose)() | 释放当前实例。 |

### 备注

**Learn more:**

* [Adding image watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks)

### 示例

向任何受支持类型的文档添加图像水印。

```csharp
foreach (string filePath in Directory.GetFiles(@"C:\Documents"))
{
    using (Watermarker watermarker = new Watermarker(filePath))
    {
        using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
        {
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            watermarker.Add(watermark);
        }

        watermarker.Save();
    }
}
```

### 另请参阅

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
