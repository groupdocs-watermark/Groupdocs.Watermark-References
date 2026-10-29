---
title: "PresentationWatermarkableImage"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示 PowerPoint 文档中的图像。"
type: docs
weight: 1090
url: /zh/net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/
---
## PresentationWatermarkableImage class

表示 PowerPoint 文档中的图像。

```csharp
public class PresentationWatermarkableImage : WatermarkableImage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PresentationWatermarkableImage](presentationwatermarkableimage)(byte[]) | 使用指定的图像数据初始化 [`PresentationWatermarkableImage`](../presentationwatermarkableimage) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | 获取此 [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) 的高度（像素）。 |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | 获取此 [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) 的宽度（像素）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | 向此 [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) 添加水印。此方法假设水印的偏移量和大小以像素为单位（如果已分配）。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | 在内容中查找所有图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 根据指定的搜索条件查找图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | 获取图像的字节数组。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | 在内容中查找所有可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 根据指定的搜索条件查找可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |

### 另请参阅

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
