---
title: AddAttachment
second_title: .NET API 参考的 GroupDocs.Watermark
description: 将附件添加到SpreadsheetWorksheetgroupdocs.watermark.contents.spreadsheet/spreadsheetworksheet.
type: docs
weight: 10
url: /zh/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment/
---
## SpreadsheetAttachmentCollection.AddAttachment method

将附件添加到[`SpreadsheetWorksheet`](../../spreadsheetworksheet).

```csharp
public void AddAttachment(byte[] fileContent, string sourceFullName, byte[] previewImageContent, 
    double x, double y, double width, double height)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileContent | Byte[] | 要附加的文件的内容。 |
| sourceFullName | String | 附件的全名（扩展名用于 确定合适的应用程序打开文件）。 |
| previewImageContent | Byte[] | 作为字节数组的附件预览图像。 |
| x | Double | 附件框架的 x 坐标（以磅为单位）。 |
| y | Double | 附件框架的 y 坐标（以磅为单位）。 |
| width | Double | 附件框架的宽度（以磅为单位）。 |
| height | Double | 附件框架的高度（以磅为单位）。 |

### 也可以看看

* class [SpreadsheetAttachmentCollection](../../spreadsheetattachmentcollection)
* 命名空间 [GroupDocs.Watermark.Contents.Spreadsheet](../../spreadsheetattachmentcollection)
* 部件 [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->