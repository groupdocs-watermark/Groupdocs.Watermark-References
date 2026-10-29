---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل خيارات عند إضافة العلامة المائية كخلفية إلى ورقة عمل Spreadsheet."
type: docs
weight: 2190
url: /ar/net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
---
## SpreadsheetBackgroundWatermarkOptions class

يمثل خيارات عند إضافة العلامة المائية كخلفية إلى ورقة عمل Spreadsheet.

```csharp
public sealed class SpreadsheetBackgroundWatermarkOptions : WatermarkOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SpreadsheetBackgroundWatermarkOptions](spreadsheetbackgroundwatermarkoptions)() | يقوم بتهيئة نسخة جديدة من الفئة [`SpreadsheetBackgroundWatermarkOptions`](../spreadsheetbackgroundwatermarkoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundHeight](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundheight) { get; set; } | يحصل أو يعيّن الارتفاع المطلوب لصورة الخلفية بالبكسل. |
| [BackgroundWidth](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundwidth) { get; set; } | يحصل أو يعيّن العرض المطلوب لصورة الخلفية بالبكسل. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheetindex) { get; set; } | يحصل أو يعيّن فهرس ورقة العمل لإضافة العلامة المائية إليها. |

### ملاحظات

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### أمثلة

إضافة علامة مائية نصية إلى ورقة عمل مستند Excel كخلفية.

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

### انظر أيضاً

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
