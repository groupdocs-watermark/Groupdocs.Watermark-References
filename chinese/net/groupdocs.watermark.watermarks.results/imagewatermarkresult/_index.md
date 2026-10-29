---
title: "ImageWatermarkResult"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "包含图像水印属性。"
type: docs
weight: 3260
url: /zh/net/groupdocs.watermark.watermarks.results/imagewatermarkresult/
---
## ImageWatermarkResult class

包含图像水印属性。

```csharp
public class ImageWatermarkResult : BaseWatermarkResult
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageWatermarkResult](imagewatermarkresult)(string) | 使用在搜索过程后获得的水印标识符初始化 ImageWatermarkResult 对象。此唯一标识符用于从文档水印信息层查找该水印的其他属性。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CreatedOn](../../groupdocs.watermark.watermarks.results/basewatermarkresult/createdon) { get; set; } | 获取或设置水印的创建日期。 |
| [Height](../../groupdocs.watermark.watermarks.results/basewatermarkresult/height) { get; set; } | 指定水印的高度。 |
| [Left](../../groupdocs.watermark.watermarks.results/basewatermarkresult/left) { get; set; } | 指定水印的左侧位置。 |
| [ModifiedOn](../../groupdocs.watermark.watermarks.results/basewatermarkresult/modifiedon) { get; set; } | 获取或设置水印的修改日期。 |
| [PageNumber](../../groupdocs.watermark.watermarks.results/basewatermarkresult/pagenumber) { get; } | 指定放置水印的页面。 |
| [Size](../../groupdocs.watermark.watermarks.results/imagewatermarkresult/size) { get; } | 指定水印图像的字节大小。 |
| [Top](../../groupdocs.watermark.watermarks.results/basewatermarkresult/top) { get; set; } | 指定水印的顶部位置。 |
| [WatermarkId](../../groupdocs.watermark.watermarks.results/basewatermarkresult/watermarkid) { get; } | 唯一的水印标识符，用于在文档中通过 Update 或 Delete 方法修改水印。此属性将在调用 Add 方法后自动设置。如果此属性之前已保存，则可以手动设置以操作水印。 |
| [WatermarkPosition](../../groupdocs.watermark.watermarks.results/basewatermarkresult/watermarkposition) { get; } | 指定水印位置 |
| [WatermarkType](../../groupdocs.watermark.watermarks.results/basewatermarkresult/watermarktype) { get; } | 指定水印的类型。 |
| [Width](../../groupdocs.watermark.watermarks.results/basewatermarkresult/width) { get; set; } | 指定水印的宽度。 |

### 另请参阅

* class [BaseWatermarkResult](../basewatermarkresult)
* namespace [GroupDocs.Watermark.Watermarks.Results](../../groupdocs.watermark.watermarks.results)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
