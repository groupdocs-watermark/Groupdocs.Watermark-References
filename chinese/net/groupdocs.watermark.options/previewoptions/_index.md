---
title: PreviewOptions
second_title: .NET API 参考的 GroupDocs.Watermark
description: 提供选项来设置预览生成的要求和流代理
type: docs
weight: 2070
url: /zh/net/groupdocs.watermark.options/previewoptions/
---
## PreviewOptions class

提供选项来设置预览生成的要求和流代理。

```csharp
public class PreviewOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream) | 初始化[`PreviewOptions`](../previewoptions)导致输出流关闭的类。 |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | 初始化一个新的实例[`PreviewOptions`](../previewoptions)类导致输出流返回 给客户端以供进一步使用。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | 获取或设置页面流创建委托的实例。 |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | 获取或设置页面预览高度。 |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | 获取或设置页码数组以生成预览。 |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | 获取或设置预览图像格式 |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | 获取或设置页面预览完成委托的实例。 |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | 获取或设置页面预览宽度。 |

### 也可以看看

* 命名空间 [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* 部件 [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->