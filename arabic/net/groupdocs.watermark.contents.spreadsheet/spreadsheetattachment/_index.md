---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل ملفًا مرفقًا بمستند Excel."
type: docs
weight: 1100
url: /ar/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/
---
## SpreadsheetAttachment class

يمثل ملفًا مرفقًا بمستند Excel.

```csharp
public class SpreadsheetAttachment : Attachment, ITwoDObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/alternativetext) { get; set; } | يحصل أو يعيّن النص الوصفي (البديل) المرتبط بالملف المرفق. |
| override [Content](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/content) { get; set; } | يسترجع أو يعيّن محتوى الملف المرفق. |
| [Height](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/height) { get; set; } | يحصل أو يعيّن ارتفاع إطار المرفق بالنقاط. |
| [IsLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/islink) { get; } | يحصل على قيمة تشير إلى ما إذا كان المحتوى يحتوي فقط على رابط إلى الملف. |
| [PreviewImageContent](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/previewimagecontent) { get; set; } | يحصل أو يعيّن صورة معاينة الملف المرفق كمصفوفة بايت. |
| [SourceFullName](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/sourcefullname) { get; } | يحصل على الاسم الكامل للملف المرفق. |
| [Width](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/width) { get; set; } | يحصل أو يعيّن عرض إطار المرفق بالنقاط. |
| [X](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/x) { get; set; } | يحصل أو يعيّن الإزاحة الأفقية لإطار المرفق من الحد الأيسر لورقة العمل بالنقاط. |
| [Y](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/y) { get; set; } | يحصل أو يعيّن الإزاحة العمودية لإطار المرفق من الحد العلوي لورقة العمل بالنقاط. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | يحمّل محتوىً من الملف المرفق. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | يحمّل محتوىً من الملف المرفق مع خيارات التحميل المحددة. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | يحمّل محتوىً من الملف المرفق مع خيارات التحميل المحددة والإعدادات. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | يسترجع المعلومات حول مستند مخزن في الملف المرفق. |

### انظر أيضاً

* class [Attachment](../../groupdocs.watermark.common/attachment)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
