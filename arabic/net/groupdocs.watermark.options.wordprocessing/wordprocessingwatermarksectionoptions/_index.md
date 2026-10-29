---
title: "WordProcessingWatermarkSectionOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل الخيارات عند إضافة علامة مائية شكل إلى قسم وثيقة Word."
type: docs
weight: 2420
url: /ar/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/
---
## WordProcessingWatermarkSectionOptions class

يمثل الخيارات عند إضافة علامة مائية شكل إلى قسم وثيقة Word.

```csharp
public sealed class WordProcessingWatermarkSectionOptions : WordProcessingWatermarkBaseOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WordProcessingWatermarkSectionOptions](wordprocessingwatermarksectionoptions)() | ينشئ مثيلاً جديداً للفئة [`WordProcessingWatermarkSectionOptions`](../wordprocessingwatermarksectionoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | يحصل أو يعيّن النص الوصفي (البديل) الذي سيُرتبط بشكل. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | يحصل أو يعيّن قيمة من [`WordProcessingImageEffects`](../wordprocessingimageeffects) أو [`WordProcessingTextEffects`](../wordprocessingtexteffects) للتأثيرات التي يجب تطبيقها على العلامة المائية. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تحرير الشكل في Word محظورًا. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | يحصل أو يعيّن نوع قفل العلامة المائية. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | يحصل أو يعيّن اسم الشكل. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | يحصل أو يعيّن كلمة مرور تُستخدم لقفل العلامة المائية. |
| [SectionIndex](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarksectionoptions/sectionindex) { get; set; } | يحصل أو يعيّن فهرس القسم لإضافة العلامة المائية إليه. |

### ملاحظات

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### أمثلة

إضافة علامة مائية إلى قسم معين من مستند Word.

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.doc", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;
    watermark.ForegroundColor = Color.Red;

    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
    options.SectionIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### انظر أيضاً

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
