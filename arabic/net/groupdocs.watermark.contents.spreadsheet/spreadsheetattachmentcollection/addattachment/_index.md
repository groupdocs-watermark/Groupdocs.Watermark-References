---
title: "AddAttachment"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يضيف مرفقًا إلى SpreadsheetWorksheetgroupdocs.watermark.contents.spreadsheet/spreadsheetworksheet."
type: docs
weight: 10
url: /ar/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment/
---
## SpreadsheetAttachmentCollection.AddAttachment method

يضيف مرفقًا إلى [`SpreadsheetWorksheet`](../../spreadsheetworksheet).

```csharp
public void AddAttachment(byte[] fileContent, string sourceFullName, byte[] previewImageContent, 
    double x, double y, double width, double height)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| fileContent | Byte[] | محتوى الملف المراد إرفاقه. |
| sourceFullName | String | الاسم الكامل للملف المرفق (يُستخدم الامتداد لتحديد التطبيق المناسب لفتح الملف). |
| previewImageContent | Byte[] | صورة معاينة الملف المرفق كمصفوفة بايت. |
| x | Double | الإحداثي السيني لإطار المرفق (بالنقاط). |
| y | Double | الإحداثي الصادي لإطار المرفق (بالنقاط). |
| width | Double | عرض إطار المرفق بالنقاط. |
| height | Double | ارتفاع إطار المرفق بالنقاط. |

### انظر أيضاً

* class [SpreadsheetAttachmentCollection](../../spreadsheetattachmentcollection)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
