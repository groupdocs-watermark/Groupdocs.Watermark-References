---
title: "PresentationWatermarkSlideOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示在向 Presentation 文档幻灯片添加水印时的选项。"
type: docs
weight: 2130
url: /zh/net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/
---
## PresentationWatermarkSlideOptions class

表示在向 Presentation 文档幻灯片添加水印时的选项。

```csharp
public sealed class PresentationWatermarkSlideOptions : PresentationWatermarkBaseSlideOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PresentationWatermarkSlideOptions](presentationwatermarkslideoptions)() | 初始化一个新的 [`PresentationWatermarkSlideOptions`](../presentationwatermarkslideoptions) 类的实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | 获取或设置将与形状关联的描述性（替代）文本。 |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | 获取或设置 [`PresentationImageEffects`](../presentationimageeffects) 或 [`PresentationTextEffects`](../presentationtexteffects) 的值，以指定应应用于水印的效果。 |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | 获取或设置一个值，指示是否禁止在 PowerPoint 中编辑形状。 |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | 获取或设置形状的名称。 |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | 获取或设置一个值，指示文本水印字符是否与不可读字符混合。 |
| [SlideIndex](../../groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/slideindex) { get; set; } | 获取或设置要添加水印的幻灯片的索引。 |

### 备注

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### 示例

向 Power Point 演示文稿的特定幻灯片添加水印。

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.ppt", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;

    PresentationWatermarkSlideOptions options = new PresentationWatermarkSlideOptions();
    options.SlideIndex = 0;
    options.IsLocked = false; // default
    options.ProtectWithUnreadableCharacters = false; // default
    options.Name = null; // default
    options.AlternativeText = null; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 另请参阅

* class [PresentationWatermarkBaseSlideOptions](../presentationwatermarkbaseslideoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
