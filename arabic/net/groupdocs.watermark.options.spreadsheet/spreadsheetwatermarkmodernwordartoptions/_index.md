---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل الخيارات عند إضافة علامة مائية فن كلمة حديثة إلى ورقة عمل Spreadsheet."
type: docs
weight: 2280
url: /ar/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/
---
## SpreadsheetWatermarkModernWordArtOptions class

يمثل الخيارات عند إضافة علامة مائية فن كلمة حديثة إلى ورقة عمل Spreadsheet.

```csharp
public sealed class SpreadsheetWatermarkModernWordArtOptions : SpreadsheetWatermarkBaseOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SpreadsheetWatermarkModernWordArtOptions](spreadsheetwatermarkmodernwordartoptions)() | يقوم بتهيئة نسخة جديدة من الفئة [`SpreadsheetWatermarkModernWordArtOptions`](../spreadsheetwatermarkmodernwordartoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternativetext) { get; set; } | يحصل أو يعيّن النص الوصفي (البديل) الذي سيُرتبط بشكل. |
| [IsLocked](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/islocked) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان تعديل الشكل في Excel محظوراً. |
| [Name](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name) { get; set; } | يحصل أو يعيّن اسم الشكل. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/worksheetindex) { get; set; } | يحصل أو يعيّن فهرس ورقة العمل لإضافة العلامة المائية إليها. |

### ملاحظات

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### أمثلة

إضافة علامة مائية WordArt حديثة إلى مستند Excel.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xls", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));

    SpreadsheetWatermarkModernWordArtOptions options = new SpreadsheetWatermarkModernWordArtOptions();
    options.WorksheetIndex = -1; // default
    options.IsLocked = false; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### انظر أيضاً

* class [SpreadsheetWatermarkBaseOptions](../spreadsheetwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
