---
title: "PresentationWatermarkSlideOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل الخيارات عند إضافة العلامة المائية إلى شريحة مستند Presentation."
type: docs
weight: 2130
url: /ar/net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/
---
## PresentationWatermarkSlideOptions class

يمثل الخيارات عند إضافة العلامة المائية إلى شريحة مستند Presentation.

```csharp
public sealed class PresentationWatermarkSlideOptions : PresentationWatermarkBaseSlideOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PresentationWatermarkSlideOptions](presentationwatermarkslideoptions)() | يُنشئ مثيلاً جديدًا للفئة [`PresentationWatermarkSlideOptions`](../presentationwatermarkslideoptions) class. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | يحصل أو يعيّن النص الوصفي (البديل) الذي سيُرتبط بشكل. |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | يحصل أو يضبط قيمة [`PresentationImageEffects`](../presentationimageeffects) أو [`PresentationTextEffects`](../presentationtexteffects) للتأثيرات التي يجب تطبيقها على العلامة المائية. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تحرير الشكل في PowerPoint محظوراً. |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | يحصل أو يعيّن اسم الشكل. |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة. |
| [SlideIndex](../../groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/slideindex) { get; set; } | يحصل أو يعيّن فهرس الشريحة التي ستُضاف إليها العلامة المائية. |

### ملاحظات

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### أمثلة

أضف علامة مائية إلى شريحة معينة في عرض Power Point.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.ppt", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;

    PresentationWatermarkSlideOptions options = new PresentationWatermarkSlideOptions();
    options.SlideIndex = 0;
    options.IsLocked = false; // default
    options.ProtectWithUnreadableCharacters = false; // default
    options.Name = null; // default
    options.AlternativeText = null; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### انظر أيضاً

* class [PresentationWatermarkBaseSlideOptions](../presentationwatermarkbaseslideoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
