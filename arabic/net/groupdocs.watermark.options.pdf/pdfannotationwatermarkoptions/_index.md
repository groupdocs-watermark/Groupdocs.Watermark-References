---
title: "PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية توضيحية إلى مستند PDF."
type: docs
weight: 1930
url: /ar/net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
---
## PdfAnnotationWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية توضيحية إلى مستند PDF.

```csharp
public sealed class PdfAnnotationWatermarkOptions : PdfWatermarkOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfAnnotationWatermarkOptions](pdfannotationwatermarkoptions)() | يقوم بإنشاء نسخة جديدة من الفئة [`PdfAnnotationWatermarkOptions`](../pdfannotationwatermarkoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/pageindex) { get; set; } | يحصل أو يعيّن فهرس الصفحة لإضافة العلامة المائية إليها. |
| [PrintOnly](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/printonly) { get; set; } | يحصل أو يعيّن القيمة التي تشير إلى ما إذا كانت التعليقات ستُطبع، ولكن لن تُعرض في تطبيق عرض PDF. |

### ملاحظات

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### أمثلة

أضف علامة مائية لتعليق صورة إلى مستند PDF.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
    }

    watermarker.Save();
}
```

### انظر أيضاً

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
