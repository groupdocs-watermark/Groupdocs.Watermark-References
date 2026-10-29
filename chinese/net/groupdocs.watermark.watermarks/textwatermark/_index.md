---
title: "TextWatermark"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示文本水印。"
type: docs
weight: 3320
url: /zh/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

表示文本水印。

```csharp
public class TextWatermark : Watermark
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | 使用指定的文本和字体初始化 [`TextWatermark`](../textwatermark) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | 获取或设置文本的背景颜色。 |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | 获取或设置一个值，指示是否在计算水印大小和坐标时考虑父级边距。 |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | 获取或设置文本的字体。 |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | 获取或设置文本的前景颜色。 |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的期望高度。 |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的水平对齐方式。 |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | 获取或设置一个值，指示是否应将水印放置在背景中。 |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的边距设置。 |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的不透明度。 |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | 获取或设置此[`TextWatermark`](../textwatermark)的填充设置。此属性仅适用于图像文件。 |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的页面设置。 |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的旋转角度（以度为单位）。 |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | 获取或设置一个值，指示是否在文档元数据中保存已添加水印的信息。 |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | 获取或设置一个值，定义水印大小如何依赖于父级大小。 |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | 获取或设置一个值，指定水印的尺寸方式。 |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | 获取或设置用作水印的文本。 |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | 获取或设置水印文本的对齐方式。 |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | 获取或设置用于定义重复水印的选项 |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的垂直对齐方式。 |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的期望宽度。 |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的 X 坐标。 |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | 获取或设置此[`Watermark`](../../groupdocs.watermark/watermark)的 Y 坐标。 |

### 备注

**Learn more:**

* [Adding text watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### 示例

根据父级大小缩放文本水印。

```csharp
foreach (string file in Directory.GetFiles("C:\\test"))
{
    using (Watermarker watermarker = new Watermarker(file))
    {
        TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
        watermark.HorizontalAlignment = HorizontalAlignment.Center;
        watermark.VerticalAlignment = VerticalAlignment.Center;
        watermark.SizingType = SizingType.ScaleToParentDimensions;
        watermark.RotateAngle = 45;
        watermark.ScaleFactor = 0.4;

        watermarker.Add(watermark);
        watermarker.Save();
    }
}
```

### 另请参阅

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
