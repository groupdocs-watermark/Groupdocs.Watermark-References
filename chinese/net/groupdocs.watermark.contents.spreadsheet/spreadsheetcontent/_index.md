---
title: "SpreadsheetContent"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示可以放置水印的 Excel 文档。"
type: docs
weight: 1170
url: /zh/net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
---
## SpreadsheetContent class

表示可以放置水印的 Excel 文档。

```csharp
public class SpreadsheetContent : Content
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Worksheets](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets) { get; } | 获取此 [`SpreadsheetContent`](../spreadsheetcontent) 的所有工作表集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt)() | 解密文档。 |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | 释放当前实例。 |
| [Encrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt)(string) | 加密内容。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | 在内容中查找所有图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 根据指定的搜索条件查找图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | 在内容中查找所有可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 根据指定的搜索条件查找可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |

### 备注

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)
* [Shapes in spreadsheet document](https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document)
* [Working with spreadsheet document attachments](https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments)
* [Working with worksheet backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds)
* [Working with worksheet headers and footers](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers)

### 示例

加载和保存任何受支持类型的 Excel 文档。

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.xls", loadOptions))
{
    // 使用 Add 方法向特定或所有工作表添加水印。

    // 保存更改。
    watermarker.Save(@"D:\output.xls");
}
```

### 另请参阅

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
