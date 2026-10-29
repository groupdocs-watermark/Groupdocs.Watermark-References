---
title: "SearchableObjects"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "获取或设置要包含在水印搜索中的内容对象。"
type: docs
weight: 20
url: /zh/net/groupdocs.watermark/watermarker/searchableobjects/
---
## Watermarker.SearchableObjects property

获取或设置要包含在水印搜索中的内容对象。

```csharp
public SearchableObjects SearchableObjects { get; set; }
```

### Property Value

将在水印搜索中包含的对象。

### 备注

此属性还指定用于图像搜索的内容对象。更多信息请参阅[`Search`](../search)和[`GetImages`](../getimages)方法。

了解更多关于搜索水印的信息: [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)。

### 示例

从 PDF 文档中移除所有 XObjects 和 Artifacts。

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf"))
{
    // 指定仅搜索 XObjects 和 Artifacts。
    watermarker.SearchableObjects.PdfSearchableObjects
        = PdfSearchableObjects.XObjects | PdfSearchableObjects.Artifacts; 

    PossibleWatermarkCollection watermarks = watermarker.Search();

    // 移除所有找到的对象。
    watermarks.Clear();

    // 保存更改。
    watermarker.Save();
}
```

### 另请参阅

* class [SearchableObjects](../../../groupdocs.watermark.search.objects/searchableobjects)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
