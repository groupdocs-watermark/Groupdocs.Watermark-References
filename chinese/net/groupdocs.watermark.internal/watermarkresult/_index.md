---
title: "WatermarkResult"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示水印操作的结果，包括文档大小、处理时间以及已应用水印的数量等详细信息。"
type: docs
weight: 1670
url: /zh/net/groupdocs.watermark.internal/watermarkresult/
---
## WatermarkResult class

表示水印操作的结果，包括文档大小、处理时间以及已应用水印的数量等详细信息。

```csharp
public class WatermarkResult
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WatermarkResult](watermarkresult#constructor)() | 初始化一个新的 [`WatermarkResult`](../watermarkresult) 类实例。 |
| [WatermarkResult](watermarkresult#constructor_1)(long, TimeSpan, long, int) | 使用特定值初始化一个新的 [`WatermarkResult`](../watermarkresult) 类实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FinalDocumentSize](../../groupdocs.watermark.internal/watermarkresult/finaldocumentsize) { get; } | 获取或设置最终处理文档的大小（字节）。 |
| [NumberWatermarksApplied](../../groupdocs.watermark.internal/watermarkresult/numberwatermarksapplied) { get; } | 获取或设置文档中已应用的水印总数。 |
| [ProcessingTime](../../groupdocs.watermark.internal/watermarkresult/processingtime) { get; } | 获取或设置水印操作的处理时间。 |
| [SourceDocumentSize](../../groupdocs.watermark.internal/watermarkresult/sourcedocumentsize) { get; } | 获取或设置源文档的大小（字节）。 |

### 另请参阅

* namespace [GroupDocs.Watermark.Internal](../../groupdocs.watermark.internal)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
