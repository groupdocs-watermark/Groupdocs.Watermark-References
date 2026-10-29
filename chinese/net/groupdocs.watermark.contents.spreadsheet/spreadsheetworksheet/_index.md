---
title: "SpreadsheetWorksheet"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示 Excel 文档工作表。"
type: docs
weight: 1330
url: /zh/net/groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/
---
## SpreadsheetWorksheet class

表示 Excel 文档工作表。

```csharp
public class SpreadsheetWorksheet : ContentPart
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/attachments) { get; } | 获取此 [`SpreadsheetWorksheet`](../spreadsheetworksheet) 的所有附件集合。 |
| [BackgroundImage](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/backgroundimage) { get; set; } | 获取或设置此 [`SpreadsheetWorksheet`](../spreadsheetworksheet) 的背景图像。 |
| [Charts](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/charts) { get; } | 获取此 [`SpreadsheetWorksheet`](../spreadsheetworksheet) 的所有图表集合。 |
| [ContentAreaHeight](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/contentareaheight) { get; } | 获取内容区域的高度（单位：点）。 |
| [ContentAreaHeightPx](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/contentareaheightpx) { get; } | 获取内容区域的高度（单位：像素）。 |
| [ContentAreaWidth](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/contentareawidth) { get; } | 获取内容区域的宽度（单位：点）。 |
| [ContentAreaWidthPx](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/contentareawidthpx) { get; } | 获取内容区域的宽度（单位：像素）。 |
| [HeadersFooters](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/headersfooters) { get; } | 获取工作表页眉和页脚的集合。 |
| [PageSetup](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/pagesetup) { get; } | 获取此 [`SpreadsheetWorksheet`](../spreadsheetworksheet) 的打印页面设置。 |
| [Shapes](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/shapes) { get; } | 获取此 [`SpreadsheetWorksheet`](../spreadsheetworksheet) 的所有形状集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | 在内容中查找所有图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | 根据指定的搜索条件查找图像。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [GetColumnWidth](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/getcolumnwidth)(int) | 获取指定列的宽度（单位：点）。 |
| [GetColumnWidthPx](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/getcolumnwidthpx)(int) | 获取指定列的宽度（单位：像素）。 |
| [GetRowHeight](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/getrowheight)(int) | 获取指定行的高度（单位：点）。 |
| [GetRowHeightPx](../../groupdocs.watermark.contents.spreadsheet/spreadsheetworksheet/getrowheightpx)(int) | 获取指定行的高度（单位：像素）。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | 在内容中查找所有可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | 根据指定的搜索条件查找可能的水印。搜索在 [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) 指定的对象中进行。 |

### 另请参阅

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
