---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل صورة داخل مستند."
type: docs
weight: 470
url: /ar/net/groupdocs.watermark.contents.image/watermarkableimage/
---
## WatermarkableImage class

يمثل صورة داخل مستند.

```csharp
public abstract class WatermarkableImage : ContentPart
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | يعيد ارتفاع هذا [`WatermarkableImage`](../watermarkableimage) بوحدات البكسل. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | يعيد عرض هذا [`WatermarkableImage`](../watermarkableimage) بوحدات البكسل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | يضيف علامة مائية إلى هذا [`WatermarkableImage`](../watermarkableimage). تفترض هذه الطريقة أن إزاحة العلامة المائية وحجمها مقاسان بالبكسل (إذا تم تعيينهما). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | يجد جميع الصور في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | يجد الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | يحصل على الصورة كمصفوفة بايت. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | يجد جميع العلامات المائية الممكنة في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم إجراء البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### ملاحظات

**Learn more:**

* [Adding watermark to images inside a document](https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

### أمثلة

أضف علامة مائية إلى جميع الصور داخل مستند من أي نوع مدعوم.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // تهيئة علامة مائية نصية أو صورة.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // ابحث عن جميع الصور في المحتوى.
    WatermarkableImageCollection images = watermarker.GetImages();

    // أضف علامة مائية.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.Add(watermark);
    }

    // احفظ التغييرات.
    watermarker.Save(@"D:\output.doc");
}
```

### انظر أيضاً

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
