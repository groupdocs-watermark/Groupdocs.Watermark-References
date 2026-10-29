---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى ملف GIF."
type: docs
weight: 1830
url: /ar/net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
---
## GifImageWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى ملف GIF.

```csharp
public sealed class GifImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor)() | يقوم بتهيئة نسخة جديدة من الفئة [`GifImageWatermarkOptions`](../gifimagewatermarkoptions). |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor_1)(int) | يقوم بتهيئة نسخة جديدة من الفئة [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) مع فهرس محدد للإطار. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | يحصل أو يعيّن فهرس الإطار لإضافة العلامة المائية. |

### ملاحظات

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### أمثلة

أضف علامة مائية إلى إطار معين من صورة GIF.

```csharp
GifImageLoadOptions loadOptions = new GifImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### انظر أيضاً

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
