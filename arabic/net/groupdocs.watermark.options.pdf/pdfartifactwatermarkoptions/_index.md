---
title: PdfArtifactWatermarkOptions
second_title: GroupDocs.Watermark لـ .NET API Reference
description: يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية أثرية إلى مستند pdf.
type: docs
weight: 1870
url: /ar/net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
---
## PdfArtifactWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية أثرية إلى مستند pdf.

```csharp
public sealed class PdfArtifactWatermarkOptions : PdfWatermarkOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfArtifactWatermarkOptions](pdfartifactwatermarkoptions)() | يقوم بتهيئة مثيل جديد لملف[`PdfArtifactWatermarkOptions`](../pdfartifactwatermarkoptions) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/pageindex) { get; set; } | الحصول على أو تعيين فهرس الصفحة لإضافة العلامة المائية إليه. |

### ملاحظات

**يتعلم أكثر:**

* [أضف علامات مائية إلى مستندات PDF](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### أمثلة

أضف علامة مائية على شكل صورة إلى مستند PDF.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        watermark.HorizontalAlignment = HorizontalAlignment.Right;
        watermark.VerticalAlignment = VerticalAlignment.Bottom;

        PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
        options.PageIndex = -1; // افتراضي - كل الصفحات

        watermarker.Add(watermark, options);
        watermarker.Save();
    }
}
```

### أنظر أيضا

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* مساحة الاسم [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* المجسم [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->