---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية أثرية إلى مستند PDF."
type: docs
weight: 1940
url: /ar/net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
---
## PdfArtifactWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية أثرية إلى مستند PDF.

```csharp
public sealed class PdfArtifactWatermarkOptions : PdfWatermarkOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfArtifactWatermarkOptions](pdfartifactwatermarkoptions)() | يقوم بإنشاء نسخة جديدة من الفئة [`PdfArtifactWatermarkOptions`](../pdfartifactwatermarkoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/pageindex) { get; set; } | يحصل أو يعيّن فهرس الصفحة لإضافة العلامة المائية إليها. |

### ملاحظات

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### أمثلة

أضف علامة مائية لصورة أثرية إلى مستند PDF.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        watermark.HorizontalAlignment = HorizontalAlignment.Right;
        watermark.VerticalAlignment = VerticalAlignment.Bottom;

        PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
        watermarker.Save();
    }
}
```

### انظر أيضاً

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
