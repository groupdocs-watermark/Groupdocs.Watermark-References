---
title: "SpreadsheetSearchableObjects"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "指定表示要包含在水印搜索中的 Excel 内容对象的标志。"
type: docs
weight: 2560
url: /zh/net/groupdocs.watermark.search.objects/spreadsheetsearchableobjects/
---
## SpreadsheetSearchableObjects enumeration

指定表示要包含在水印搜索中的 Excel 内容对象的标志。

```csharp
[Flags]
public enum SpreadsheetSearchableObjects
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 指定没有搜索对象。 |
| Shapes | `1` | 在形状中搜索。 |
| ChartsBackgrounds | `2` | 在图表背景中搜索。 |
| HeadersFooters | `4` | 在页眉和页脚中搜索。 |
| WorksheetBackgrounds | `8` | 在工作表背景中搜索。 |
| Cells | `10` | 在单元格中搜索。 |
| Hyperlinks | `20` | 在超链接中搜索。 |
| AttachedImages | `40` | 在附件图像中搜索。 |
| All | `7F` | 在所有内容对象中搜索。 |

### 另请参阅

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
