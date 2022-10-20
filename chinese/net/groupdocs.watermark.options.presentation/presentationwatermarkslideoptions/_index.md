---
title: PresentationWatermarkSlideOptions
second_title: .NET API 参考的 GroupDocs.Watermark
description: 表示向演示文档幻灯片添加水印时的选项
type: docs
weight: 2060
url: /zh/net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/
---
## PresentationWatermarkSlideOptions class

表示向演示文档幻灯片添加水印时的选项。

```csharp
public sealed class PresentationWatermarkSlideOptions : PresentationWatermarkBaseSlideOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PresentationWatermarkSlideOptions](presentationwatermarkslideoptions)() | 初始化[`PresentationWatermarkSlideOptions`](../presentationwatermarkslideoptions)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | 获取或设置将与形状关联的描述性（替代）文本。 |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | 获取或设置一个值[`PresentationImageEffects`](../presentationimageeffects)or [`PresentationTextEffects`](../presentationtexteffects)对于应该应用于水印的效果。 |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | 获取或设置一个值，该值指示是否禁止在 PowerPoint 中编辑形状。 |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | 获取或设置形状的名称。 |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | 获取或设置一个值，该值指示文本水印字符是否与不可读字符混合。 |
| [SlideIndex](../../groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/slideindex) { get; set; } | 获取或设置要添加水印的幻灯片的索引。 |

### 评论

**学到更多：**

* [为演示文稿添加水印](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### 例子

为 Power Point 演示文稿的特定幻灯片添加水印。

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.ppt", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;

    PresentationWatermarkSlideOptions options = new PresentationWatermarkSlideOptions();
    options.SlideIndex = 0;
    options.IsLocked = false; // 默认
    options.ProtectWithUnreadableCharacters = false; // 默认
    options.Name = null; // 默认
    options.AlternativeText = null; // 默认

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 也可以看看

* class [PresentationWatermarkBaseSlideOptions](../presentationwatermarkbaseslideoptions)
* 命名空间 [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* 部件 [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->