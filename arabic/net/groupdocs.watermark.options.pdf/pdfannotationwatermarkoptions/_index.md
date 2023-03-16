---
title: PdfAnnotationWatermarkOptions
second_title: GroupDocs.Watermark لـ .NET API Reference
description: يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية للتعليق إلى مستند pdf.
type: docs
weight: 1860
url: /ar/net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
---
## PdfAnnotationWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية للتعليق إلى مستند pdf.

```csharp
public sealed class PdfAnnotationWatermarkOptions : PdfWatermarkOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfAnnotationWatermarkOptions](pdfannotationwatermarkoptions)() | يقوم بتهيئة مثيل جديد لملف[`PdfAnnotationWatermarkOptions`](../pdfannotationwatermarkoptions) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/pageindex) { get; set; } | الحصول على أو تعيين فهرس الصفحة لإضافة العلامة المائية إليه. |
| [PrintOnly](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/printonly) { get; set; } | احصل على القيمة أو عيّنها للإشارة إلى ما إذا كانت ستتم طباعة التعليق التوضيحي أم لا ، ولكن لن يتم عرضه في تطبيق عرض pdf. |

### ملاحظات

**يتعلم أكثر:**

* [أضف علامات مائية إلى مستندات PDF](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### أمثلة

أضف علامة مائية للتعليق التوضيحي للصورة إلى مستند PDF.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
        options.PageIndex = -1; // افتراضي - كل الصفحات

        watermarker.Add(watermark, options);
    }

    watermarker.Save();
}
```

### أنظر أيضا

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* مساحة الاسم [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* المجسم [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->