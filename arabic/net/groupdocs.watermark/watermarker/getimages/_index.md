---
title: "GetImages"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يجد الصور وفقًا لمعايير البحث المحددة."
type: docs
weight: 80
url: /ar/net/groupdocs.watermark/watermarker/getimages/
---
## GetImages(ImageSearchCriteria) {#getimages_1}

يجد الصور وفقًا لمعايير البحث المحددة.

```csharp
public WatermarkableImageCollection GetImages(ImageSearchCriteria searchCriteria)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| searchCriteria | ImageSearchCriteria | معايير البحث للاستخدام. |

### قيمة الإرجاع

مجموعة الصور المكتشفة.

### ملاحظات

يتم إجراء البحث في الكائنات المحددة في [`SearchableObjects`](../searchableobjects).

تعرف على المزيد حول البحث عن العلامات المائية [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### أمثلة

إزالة جميع الصور المشابهة للمرجع من مستند من أي نوع مدعوم.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
    WatermarkableImageCollection images = watermarker.GetImages(criteria);
    images.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### انظر أيضاً

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [ImageSearchCriteria](../../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## GetImages() {#getimages}

يجد جميع الصور في المستند.

```csharp
public WatermarkableImageCollection GetImages()
```

### قيمة الإرجاع

مجموعة الصور المكتشفة.

### ملاحظات

يتم إجراء البحث في الكائنات المحددة في [`SearchableObjects`](../searchableobjects).

تعرف على المزيد حول البحث عن العلامات المائية [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### أمثلة

أضف علامة مائية إلى جميع الصور في مستند من أي نوع مدعوم.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // تهيئة علامة مائية نصية أو صورة.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // ابحث عن جميع الصور في المستند.
    WatermarkableImageCollection images = watermarker.GetImages();

    // أضف علامة مائية.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.AddWatermark(watermark);
    }

    // احفظ التغييرات.
    watermarker.Save(@"D:\output.doc");
}
```

### انظر أيضاً

* class [WatermarkableImageCollection](../../../groupdocs.watermark.contents.image/watermarkableimagecollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
