---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل الخيارات عند إضافة العلامة المائية إلى صفحات وثيقة Word."
type: docs
weight: 2410
url: /ar/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/
---
## WordProcessingWatermarkPagesOptions class

يمثل الخيارات عند إضافة العلامة المائية إلى صفحات وثيقة Word.

```csharp
public sealed class WordProcessingWatermarkPagesOptions : WordProcessingWatermarkBaseOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WordProcessingWatermarkPagesOptions](wordprocessingwatermarkpagesoptions)() | تهيئة نسخة جديدة من الفئة [`WordProcessingWatermarkPagesOptions`](../wordprocessingwatermarkpagesoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | يحصل أو يعيّن النص الوصفي (البديل) الذي سيُرتبط بشكل. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | يحصل أو يعيّن قيمة من [`WordProcessingImageEffects`](../wordprocessingimageeffects) أو [`WordProcessingTextEffects`](../wordprocessingtexteffects) للتأثيرات التي يجب تطبيقها على العلامة المائية. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تحرير الشكل في Word محظورًا. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | يحصل أو يعيّن نوع قفل العلامة المائية. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | يحصل أو يعيّن اسم الشكل. |
| [PageNumbers](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/pagenumbers) { get; set; } | يحصل أو يعيّن أرقام الصفحات لإضافة العلامة المائية. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | يحصل أو يعيّن كلمة مرور تُستخدم لقفل العلامة المائية. |

### ملاحظات

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### أمثلة

إضافة علامة مائية إلى صفحة معينة من مستند Word.

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.doc", loadOptions))
{
    TextWatermark watermark = new TextWatermark("text", new Font("Arial", 42));

    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
    options.PageNumbers = new[] { 1 };

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### انظر أيضاً

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
