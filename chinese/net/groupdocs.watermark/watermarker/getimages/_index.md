---
title: "GetImages"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "根据指定的搜索条件查找图像。"
type: docs
weight: 80
url: /zh/net/groupdocs.watermark/watermarker/getimages/
---
## GetImages(ImageSearchCriteria) {#getimages_1}

根据指定的搜索条件查找图像。

```csharp
public WatermarkableImageCollection GetImages(ImageSearchCriteria searchCriteria)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| searchCriteria | ImageSearchCriteria | 要使用的搜索条件。 |

### 返回值

找到的图像集合。

### 备注

搜索在 [`SearchableObjects`](../searchableobjects) 中指定的对象中进行。

了解有关搜索水印的更多信息 [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)。

### 示例

从任何受支持类型的文档中移除所有与参考图像相似的图像。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
    WatermarkableImageCollection images = watermarker.GetImages(criteria);
    images.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### 另请参阅

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [ImageSearchCriteria](../../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## GetImages() {#getimages}

查找文档中的所有图像。

```csharp
public WatermarkableImageCollection GetImages()
```

### 返回值

找到的图像集合。

### 备注

搜索在 [`SearchableObjects`](../searchableobjects) 中指定的对象中进行。

了解有关搜索水印的更多信息 [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)。

### 示例

在任何受支持类型的文档中的所有图像上添加水印。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // 初始化文本或图像水印。
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // 在文档中查找所有图像。
    WatermarkableImageCollection images = watermarker.GetImages();

    // 添加水印。
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.AddWatermark(watermark);
    }

    // 保存更改。
    watermarker.Save(@"D:\output.doc");
}
```

### 另请参阅

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
