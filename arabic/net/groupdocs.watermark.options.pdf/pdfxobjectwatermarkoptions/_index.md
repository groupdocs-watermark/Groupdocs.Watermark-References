---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية XObject إلى مستند PDF."
type: docs
weight: 1990
url: /ar/net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
---
## PdfXObjectWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية XObject إلى مستند PDF.

```csharp
public sealed class PdfXObjectWatermarkOptions : PdfWatermarkOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfXObjectWatermarkOptions](pdfxobjectwatermarkoptions)() | يقوم بإنشاء نسخة جديدة من الفئة [`PdfXObjectWatermarkOptions`](../pdfxobjectwatermarkoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/pageindex) { get; set; } | يحصل أو يعيّن فهرس الصفحة لإضافة العلامة المائية إليها. |

### ملاحظات

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### أمثلة

أضف علامة مائية إلى صفحة معينة من مستند PDF.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
{
    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### انظر أيضاً

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
