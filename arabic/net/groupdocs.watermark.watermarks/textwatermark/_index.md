---
title: "TextWatermark"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل علامة مائية نصية."
type: docs
weight: 3320
url: /ar/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

يمثل علامة مائية نصية.

```csharp
public class TextWatermark : Watermark
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | يقوم بإنشاء نسخة جديدة من الفئة [`TextWatermark`](../textwatermark) بنص محدد وخط. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | يحصل أو يعيّن لون الخلفية للنص. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان حجم العلامة المائية والإحداثيات تُحسب مع مراعاة هوامش العنصر الأصلي. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | يحصل أو يعيّن خط النص. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | يحصل أو يعيّن لون المقدمة للنص. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | يحصل أو يعيّن الارتفاع المطلوب لهذه [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | يحصل أو يعيّن المحاذاة الأفقية لهذه [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب وضع العلامة المائية في الخلفية. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | يحصل أو يعيّن إعدادات الهوامش لهذه [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | يحصل أو يعيّن شفافية هذه [`Watermark`](../../groupdocs.watermark/watermark). |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | يحصل أو يعيّن إعدادات الحشو لهذه [`TextWatermark`](../textwatermark). هذه الخاصية تنطبق فقط على ملفات الصور. |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | يحصل أو يعيّن إعدادات إعداد الصفحات لهذه [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | يحصل أو يضبط زاوية الدوران لهذا [`Watermark`](../../groupdocs.watermark/watermark) بالدرجات. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب حفظ معلومات حول العلامات المائية المضافة في بيانات تعريف المستند. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | يحصل أو يعيّن قيمة تحدد كيف يعتمد حجم العلامة المائية على حجم العنصر الأصلي. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | يحصل أو يعيّن قيمة تحدد الطريقة التي يجب أن يُحجم بها العلامة المائية. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | يحصل أو يضبط النص المستخدم كعلامة مائية. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | يحصل أو يضبط محاذاة نص العلامة المائية. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | يحصل أو يعيّن خيارات لتحديد العلامة المائية المتكررة |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | يحصل أو يضبط المحاذاة العمودية لهذا [`Watermark`](../../groupdocs.watermark/watermark). |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | يحصل أو يضبط العرض المطلوب لهذا [`Watermark`](../../groupdocs.watermark/watermark). |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | يحصل أو يضبط إحداثي x لهذا [`Watermark`](../../groupdocs.watermark/watermark). |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | يحصل أو يضبط إحداثي y لهذا [`Watermark`](../../groupdocs.watermark/watermark). |

### ملاحظات

**Learn more:**

* [Adding text watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### أمثلة

قُم بتوسيع علامة النص المائية اعتمادًا على حجم العنصر الأصل.

```csharp
foreach (string file in Directory.GetFiles("C:\\test"))
{
    using (Watermarker watermarker = new Watermarker(file))
    {
        TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
        watermark.HorizontalAlignment = HorizontalAlignment.Center;
        watermark.VerticalAlignment = VerticalAlignment.Center;
        watermark.SizingType = SizingType.ScaleToParentDimensions;
        watermark.RotateAngle = 45;
        watermark.ScaleFactor = 0.4;

        watermarker.Add(watermark);
        watermarker.Save();
    }
}
```

### انظر أيضاً

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
