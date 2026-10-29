---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "表示将水印添加为电子表格工作表背景时的选项。"
type: docs
weight: 2190
url: /zh/net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
---
## SpreadsheetBackgroundWatermarkOptions class

表示将水印添加为电子表格工作表背景时的选项。

```csharp
public sealed class SpreadsheetBackgroundWatermarkOptions : WatermarkOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SpreadsheetBackgroundWatermarkOptions](spreadsheetbackgroundwatermarkoptions)() | 初始化一个新的 [`SpreadsheetBackgroundWatermarkOptions`](../spreadsheetbackgroundwatermarkoptions) 类的实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundHeight](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundheight) { get; set; } | 获取或设置背景图像的期望高度（像素）。 |
| [BackgroundWidth](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundwidth) { get; set; } | 获取或设置背景图像的期望宽度（像素）。 |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheetindex) { get; set; } | 获取或设置要添加水印的工作表索引。 |

### 备注

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### 示例

将文本水印添加到 Excel 文档工作表作为背景。

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xlsx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));

    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
    options.WorksheetIndex = -1; // default
    options.BackgroundWidth = 800;
    options.BackgroundHeight = 600;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### 另请参阅

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
