---
title: "ImageWatermark"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل علامة مائية صورة."
type: docs
weight: 3190
url: /ar/net/groupdocs.watermark.watermarks/imagewatermark/
---
## ImageWatermark class

يمثل علامة مائية صورة.

```csharp
public sealed class ImageWatermark : Watermark, IDisposable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageWatermark](imagewatermark#constructor)(Stream) | ينشئ مثيلاً جديدًا للفئة [`ImageWatermark`](../imagewatermark) مع تدفق محدد. |
| [ImageWatermark](imagewatermark#constructor_1)(string) | ينشئ مثيلاً جديدًا للفئة [`ImageWatermark`](../imagewatermark) مع مسار ملف محدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان حجم العلامة المائية والإحداثيات تُحسب مع مراعاة هوامش العنصر الأصلي. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | يحصل أو يعيّن الارتفاع المطلوب لهذه [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | يحصل أو يعيّن المحاذاة الأفقية لهذه [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب وضع العلامة المائية في الخلفية. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | يحصل أو يعيّن إعدادات الهوامش لهذه [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | يحصل أو يعيّن شفافية هذه [`Watermark`](../../groupdocs.watermark/watermark). |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | يحصل أو يعيّن إعدادات إعداد الصفحات لهذه [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | يحصل أو يضبط زاوية الدوران لهذا [`Watermark`](../../groupdocs.watermark/watermark) بالدرجات. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب حفظ معلومات حول العلامات المائية المضافة في بيانات تعريف المستند. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | يحصل أو يعيّن قيمة تحدد كيف يعتمد حجم العلامة المائية على حجم العنصر الأصلي. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | يحصل أو يعيّن قيمة تحدد الطريقة التي يجب أن يُحجم بها العلامة المائية. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | يحصل أو يعيّن خيارات لتحديد العلامة المائية المتكررة |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | يحصل أو يضبط المحاذاة العمودية لهذا [`Watermark`](../../groupdocs.watermark/watermark). |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | يحصل أو يضبط العرض المطلوب لهذا [`Watermark`](../../groupdocs.watermark/watermark). |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | يحصل أو يضبط إحداثي x لهذا [`Watermark`](../../groupdocs.watermark/watermark). |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | يحصل أو يضبط إحداثي y لهذا [`Watermark`](../../groupdocs.watermark/watermark). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.watermark.watermarks/imagewatermark/dispose)() | يتخلص من النسخة الحالية. |

### ملاحظات

**Learn more:**

* [Adding image watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks)

### أمثلة

أضف علامة مائية صورة إلى مستند من أي نوع مدعوم.

```csharp
foreach (string filePath in Directory.GetFiles(@"C:\Documents"))
{
    using (Watermarker watermarker = new Watermarker(filePath))
    {
        using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
        {
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            watermarker.Add(watermark);
        }

        watermarker.Save();
    }
}
```

### انظر أيضاً

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
