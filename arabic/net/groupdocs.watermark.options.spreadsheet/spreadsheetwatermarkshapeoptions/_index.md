---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل الخيارات عند إضافة علامة مائية على شكل إلى ورقة عمل Spreadsheet."
type: docs
weight: 2290
url: /ar/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/
---
## SpreadsheetWatermarkShapeOptions class

يمثل الخيارات عند إضافة علامة مائية على شكل إلى ورقة عمل Spreadsheet.

```csharp
public sealed class SpreadsheetWatermarkShapeOptions : SpreadsheetWatermarkBaseOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SpreadsheetWatermarkShapeOptions](spreadsheetwatermarkshapeoptions)() | يقوم بتهيئة نسخة جديدة من الفئة [`SpreadsheetWatermarkShapeOptions`](../spreadsheetwatermarkshapeoptions) class. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternativetext) { get; set; } | يحصل أو يعيّن النص الوصفي (البديل) الذي سيُرتبط بشكل. |
| [Effects](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/effects) { get; set; } | يحصل أو يعيّن قيمة من [`SpreadsheetImageEffects`](../spreadsheetimageeffects) أو [`SpreadsheetTextEffects`](../spreadsheettexteffects) للتأثيرات التي يجب تطبيقها على العلامة المائية. |
| [IsLocked](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/islocked) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان تعديل الشكل في Excel محظوراً. |
| [Name](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name) { get; set; } | يحصل أو يعيّن اسم الشكل. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/worksheetindex) { get; set; } | يحصل أو يعيّن فهرس ورقة العمل لإضافة العلامة المائية إليها. |

### ملاحظات

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### أمثلة

إضافة علامة مائية إلى ورقة عمل معينة في مستند Excel.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xls", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;

    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
    options.WorksheetIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### انظر أيضاً

* class [SpreadsheetWatermarkBaseOptions](../spreadsheetwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
