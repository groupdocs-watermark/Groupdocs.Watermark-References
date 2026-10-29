---
title: "SearchableObjects"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يحصل أو يضبط كائنات المحتوى التي سيتم تضمينها في بحث العلامة المائية."
type: docs
weight: 20
url: /ar/net/groupdocs.watermark/watermarker/searchableobjects/
---
## Watermarker.SearchableObjects property

يحصل أو يضبط كائنات المحتوى التي سيتم تضمينها في بحث العلامة المائية.

```csharp
public SearchableObjects SearchableObjects { get; set; }
```

### Property Value

الكائنات التي يجب تضمينها في بحث العلامة المائية.

### ملاحظات

تحدد هذه الخاصية أيضًا كائنات المحتوى التي تُستخدم في بحث الصور. لمزيد من المعلومات راجع طرق [`Search`](../search) و[`GetImages`](../getimages).

تعرف على المزيد حول البحث عن العلامات المائية: [البحث عن العلامات المائية](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### أمثلة

إزالة جميع XObjects وArtifacts من مستند pdf.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf"))
{
    // حدد أنه يجب البحث فقط عن XObjects وArtifacts.
    watermarker.SearchableObjects.PdfSearchableObjects
        = PdfSearchableObjects.XObjects | PdfSearchableObjects.Artifacts; 

    PossibleWatermarkCollection watermarks = watermarker.Search();

    // إزالة جميع الكائنات المكتشفة.
    watermarks.Clear();

    // احفظ التغييرات.
    watermarker.Save();
}
```

### انظر أيضاً

* class [SearchableObjects](../../../groupdocs.watermark.search.objects/searchableobjects)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
