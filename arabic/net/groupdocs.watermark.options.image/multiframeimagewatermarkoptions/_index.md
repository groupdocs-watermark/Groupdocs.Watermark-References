---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى صورة متعددة الإطارات."
type: docs
weight: 1870
url: /ar/net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
---
## MultiframeImageWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية إلى صورة متعددة الإطارات.

```csharp
public class MultiframeImageWatermarkOptions : WatermarkOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor)() | يُنشئ مثيلاً جديدًا من الفئة [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions). |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor_1)(int) | يُنشئ مثيلاً جديدًا من الفئة [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions) مع فهرس محدد للإطار. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | يحصل أو يعيّن فهرس الإطار لإضافة العلامة المائية. |

### ملاحظات

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### أمثلة

أضف علامة مائية إلى إطار معين من صورة متعددة الإطارات.

```csharp
ImageLoadOptions loadOptions = new ImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### انظر أيضاً

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
