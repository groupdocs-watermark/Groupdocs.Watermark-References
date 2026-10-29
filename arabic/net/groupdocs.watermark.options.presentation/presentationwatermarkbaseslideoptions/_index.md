---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "الفئة الأساسية لخيارات إضافة العلامة المائية إلى مستند Presentation."
type: docs
weight: 2060
url: /ar/net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
---
## PresentationWatermarkBaseSlideOptions class

الفئة الأساسية لخيارات إضافة العلامة المائية إلى مستند Presentation.

```csharp
public abstract class PresentationWatermarkBaseSlideOptions : PresentationWatermarkOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternativetext) { get; set; } | يحصل أو يعيّن النص الوصفي (البديل) الذي سيُرتبط بشكل. |
| [Effects](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects) { get; set; } | يحصل أو يضبط قيمة [`PresentationImageEffects`](../presentationimageeffects) أو [`PresentationTextEffects`](../presentationtexteffects) للتأثيرات التي يجب تطبيقها على العلامة المائية. |
| [IsLocked](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/islocked) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تحرير الشكل في PowerPoint محظوراً. |
| [Name](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name) { get; set; } | يحصل أو يعيّن اسم الشكل. |
| [ProtectWithUnreadableCharacters](../../groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protectwithunreadablecharacters) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت أحرف العلامة المائية النصية مختلطة بأحرف غير قابلة للقراءة. |

### ملاحظات

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

### أمثلة

أضف علامة مائية إلى شرائح الخدمة المختلفة في عرض Power Point.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pptx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));

    // أضف علامة مائية إلى جميع الشرائح الرئيسية
    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
    masterSlideOptions.MasterSlideIndex = -1; // default
    watermarker.Add(watermark, masterSlideOptions);

    // أضف علامة مائية إلى جميع شرائح التخطيط
    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
    layoutSlideOptions.LayoutSlideIndex = -1; // default
    watermarker.Add(watermark, layoutSlideOptions);

    // أضف علامة مائية إلى جميع شرائح الملاحظات
    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
    noteSlideOptions.SlideIndex = -1; // default
    watermarker.Add(watermark, noteSlideOptions);

    // أضف علامة مائية إلى النسخة الرئيسية للملف الموزع
    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
    watermarker.Add(watermark, masterHandoutSlideOptions);

    // أضف علامة مائية إلى النسخة الرئيسية للملاحظات
    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
    watermarker.Add(watermark, masterNotesSlideOptions);

    watermarker.Save();
}
```

### انظر أيضاً

* class [PresentationWatermarkOptions](../presentationwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
