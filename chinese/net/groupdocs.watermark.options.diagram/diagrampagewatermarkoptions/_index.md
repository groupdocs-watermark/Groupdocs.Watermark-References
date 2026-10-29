---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示在向 Visio 文档的特定页面添加形状水印时的水印添加选项."
type: docs
weight: 1720
url: /zh/net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
---
## DiagramPageWatermarkOptions class

表示在向 Visio 文档的特定页面添加形状水印时的水印添加选项.

```csharp
public sealed class DiagramPageWatermarkOptions : DiagramWatermarkOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DiagramPageWatermarkOptions](diagrampagewatermarkoptions)() | 初始化 [`DiagramPageWatermarkOptions`](../diagrampagewatermarkoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | 获取或设置一个值，指示是否禁止在 Visio 中编辑形状。 |
| [PageIndex](../../groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/pageindex) { get; set; } | 获取或设置要添加水印的页面索引。 |

### 备注

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### 示例

向 Visio 文档的第一页添加受保护的水印。

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
    options.IsLocked = true;
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 另请参阅

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
