---
title: "TiffImageWatermarkOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى صورة TIFF."
type: docs
weight: 1900
url: /ar/net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
---
## TiffImageWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى صورة TIFF.

```csharp
public sealed class TiffImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor)() | يقوم بتهيئة نسخة جديدة من الفئة [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions). |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor_1)(int) | يقوم بتهيئة نسخة جديدة من الفئة [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) مع فهرس محدد للإطار. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | يحصل أو يعيّن فهرس الإطار لإضافة العلامة المائية. |

### ملاحظات

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### أمثلة

أضف علامة مائية إلى إطار معين من صورة TIFF.

```csharp
TiffImageLoadOptions loadOptions = new TiffImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.tiff", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    TiffImageWatermarkOptions options = new TiffImageWatermarkOptions();
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
