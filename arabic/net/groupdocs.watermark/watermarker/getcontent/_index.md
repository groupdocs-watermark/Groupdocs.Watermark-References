---
title: "GetContent"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يرجع كائن Contentgroupdocs.watermark.contents/content للمستند المحمّل."
type: docs
weight: 60
url: /ar/net/groupdocs.watermark/watermarker/getcontent/
---
## Watermarker.GetContent&lt;T&gt; method

يرجع كائن [`Content`](../../../groupdocs.watermark.contents/content) للمستند المحمّل.

```csharp
public T GetContent<T>()
    where T : Content
```

| معامل | الوصف |
| --- | --- |
| T | النوع المطلوب لكائن [`Content`](../../../groupdocs.watermark.contents/content). |

### قيمة الإرجاع

كائن [`Content`](../../../groupdocs.watermark.contents/content) للمستند المحمّل.

### أمثلة

تحويل صفحة مستند PDF إلى صورة مع إضافة العلامة المائية.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
{ 
    using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
    {
        watermarker.Add(watermark);
    }

    PdfContent content = watermarker.GetContent<PdfContent>();
    content.Rasterize(300, 300, PdfImageConversionFormat.Png);

    watermarker.Save();
}
```

### انظر أيضاً

* class [Content](../../../groupdocs.watermark.contents/content)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
