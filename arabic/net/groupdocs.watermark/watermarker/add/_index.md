---
title: "Add"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يضيف علامة مائية إلى المستند المحمَّل."
type: docs
weight: 30
url: /ar/net/groupdocs.watermark/watermarker/add/
---
## Add(Watermark) {#add}

يضيف علامة مائية إلى المستند المحمَّل.

```csharp
public AddWatermarkResult Add(Watermark watermark)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| watermark | Watermark | العلامة المائية لإضافتها إلى المستند. |

### ملاحظات

تعرف على المزيد حول إضافة العلامات المائية: [إضافة العلامات المائية](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### أمثلة

أضف علامة مائية صورة ونص إلى مستند من أي نوع مدعوم.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.pdf"))
{
    TextWatermark textWatermark = new TextWatermark("DRAFT", new Font("Arial", 19));
    textWatermark.HorizontalAlignment = HorizontalAlignment.Center;
    textWatermark.VerticalAlignment = VerticalAlignment.Top;
    textWatermark.ConsiderParentMargins = true;
    textWatermark.ForegroundColor = Color.Red;
    textWatermark.IsBackground = true;
    textWatermark.Opacity = 0.5;
    watermarker.Add(textWatermark);

    using (ImageWatermark imageWatermark = new ImageWatermark(@"D:\draft.png"))
    {
        imageWatermark.HorizontalAlignment = HorizontalAlignment.Center;
        imageWatermark.VerticalAlignment = VerticalAlignment.Bottom;
        imageWatermark.ConsiderParentMargins = true;
        imageWatermark.IsBackground = true;
        imageWatermark.Opacity = 0.5;
        watermarker.Add(imageWatermark);
    }

    watermarker.Save(@"D:\output.pdf");
}
```

### انظر أيضاً

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Add(Watermark, WatermarkOptions) {#add_1}

يضيف علامة مائية إلى المستند المحمَّل باستخدام خيارات العلامة المائية.

```csharp
public AddWatermarkResult Add(Watermark watermark, WatermarkOptions options)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| watermark | Watermark | العلامة المائية لإضافتها إلى المستند. |
| options | WatermarkOptions | خيارات إضافية لاستخدامها عند إضافة العلامة المائية. |

### ملاحظات

تعرف على المزيد حول إضافة العلامات المائية [Adding watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### أمثلة

أضف علامة مائية صورة إلى صفحة معينة من مستند PDF.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
{
    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### انظر أيضاً

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [WatermarkOptions](../../../groupdocs.watermark.options/watermarkoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
