---
title: "Watermarker"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示用于文档中水印管理的类。"
type: docs
weight: 3140
url: /zh/net/groupdocs.watermark/watermarker/
---
## Watermarker class

表示用于文档中水印管理的类。

```csharp
public class Watermarker : IDisposable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | 使用指定的流初始化 [`Watermarker`](../watermarker) 类的新实例。 |
| [Watermarker](watermarker#constructor_4)(string) | 使用指定的文档路径初始化 [`Watermarker`](../watermarker) 类的新实例。 |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | 使用指定的流和加载选项初始化 [`Watermarker`](../watermarker) 类的新实例。 |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | 使用指定的流和设置初始化 [`Watermarker`](../watermarker) 类的新实例。 |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | 使用指定的文档路径和加载选项初始化 [`Watermarker`](../watermarker) 类的新实例。 |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | 使用指定的文档路径和设置初始化 [`Watermarker`](../watermarker) 类的新实例。 |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | 使用指定的流、加载选项和设置初始化 [`Watermarker`](../watermarker) 类的新实例。 |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | 使用指定的文档路径、加载选项和设置初始化 [`Watermarker`](../watermarker) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | 获取或设置要包含在水印搜索中的内容对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | 向已加载的文档添加水印。 |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | 使用水印选项向已加载的文档添加水印。 |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | 释放当前实例。 |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | 为文档生成预览图像。 |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | 返回已加载文档的 [`Content`](../../groupdocs.watermark.contents/content) 对象。 |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | 获取已加载文档格式的信息。 |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | 查找文档中的所有图像。 |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | 根据指定的搜索条件查找图像。 |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | 从文档中移除水印。 |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | 从文档中移除集合中的所有水印。 |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | 将文档数据保存到底层流。 |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | 使用保存选项将文档数据保存到底层流。 |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | 将文档保存到指定的流。 |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | 将文档保存到指定的文件位置。 |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | 使用保存选项将文档保存到指定的流。 |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | 使用保存选项将文档保存到指定的文件位置。 |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | 搜索文档中所有可能的水印。 |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | 根据指定的搜索条件搜索可能的水印。 |

### 示例

加载并保存任何受支持格式的内容。

```csharp
// 从文件加载内容。
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // 使用 Watermarker 类的方法来添加、搜索或移除水印。

    // 保存更改。
    watermarker.Save("D:\\output.pdf");
}
```

### 另请参阅

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
