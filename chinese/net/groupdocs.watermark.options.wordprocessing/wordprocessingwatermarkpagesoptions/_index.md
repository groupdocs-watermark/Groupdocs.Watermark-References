---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示向 Word 文档页面添加水印时的选项。"
type: docs
weight: 2410
url: /zh/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/
---
## WordProcessingWatermarkPagesOptions class

表示向 Word 文档页面添加水印时的选项。

```csharp
public sealed class WordProcessingWatermarkPagesOptions : WordProcessingWatermarkBaseOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WordProcessingWatermarkPagesOptions](wordprocessingwatermarkpagesoptions)() | 初始化 [`WordProcessingWatermarkPagesOptions`](../wordprocessingwatermarkpagesoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | 获取或设置将与形状关联的描述性（替代）文本。 |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | 获取或设置 [`WordProcessingImageEffects`](../wordprocessingimageeffects) 或 [`WordProcessingTextEffects`](../wordprocessingtexteffects) 的值，以指定应应用于水印的效果。 |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | 获取或设置一个值，指示是否禁止在 Word 中编辑形状。 |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | 获取或设置水印锁定类型。 |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | 获取或设置形状的名称。 |
| [PageNumbers](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/pagenumbers) { get; set; } | 获取或设置添加水印的页码。 |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | 获取或设置用于锁定水印的密码。 |

### 备注

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### 示例

向 Word 文档的特定页面添加水印。

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.doc", loadOptions))
{
    TextWatermark watermark = new TextWatermark("text", new Font("Arial", 42));

    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
    options.PageNumbers = new[] { 1 };

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 另请参阅

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
