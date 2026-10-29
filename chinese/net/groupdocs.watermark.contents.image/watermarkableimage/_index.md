---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示文档中的图像。"
type: docs
weight: 470
url: /zh/net/groupdocs.watermark.contents.image/watermarkableimage/
---
## WatermarkableImage class

表示文档中的图像。

```csharp
public abstract class WatermarkableImage : ContentPart
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | 获取此[`WatermarkableImage`](../watermarkableimage)的高度（像素）。 |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | 获取此[`WatermarkableImage`](../watermarkableimage)的宽度（像素）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | 向此[`WatermarkableImage`](../watermarkableimage)添加水印。此方法假设水印的偏移量和大小以像素为单位（如果已指定）。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | 在内容中查找所有图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 根据指定的搜索条件查找图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | 获取图像的字节数组。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | 在内容中查找所有可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 根据指定的搜索条件查找可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |

### 备注

**Learn more:**

* [Adding watermark to images inside a document](https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

### 示例

向任何受支持类型文档中的所有图像添加水印。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // 初始化文本或图像水印。
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // 在内容中查找所有图像。
    WatermarkableImageCollection images = watermarker.GetImages();

    // 添加水印。
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.Add(watermark);
    }

    // 保存更改。
    watermarker.Save(@"D:\output.doc");
}
```

### 另请参阅

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
