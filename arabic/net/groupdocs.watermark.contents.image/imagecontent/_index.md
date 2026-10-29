---
title: "ImageContent"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل صورة يمكن وضع علامة مائية عليها."
type: docs
weight: 400
url: /ar/net/groupdocs.watermark.contents.image/imagecontent/
---
## ImageContent class

يمثل صورة يمكن وضع علامة مائية عليها.

```csharp
public class ImageContent : Content
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [Height](../../groupdocs.watermark.contents.image/imagecontent/height) { get; } | يعيد ارتفاع هذا [`ImageContent`](../imagecontent) بوحدات البكسل. |
| virtual [Width](../../groupdocs.watermark.contents.image/imagecontent/width) { get; } | يعيد عرض هذا [`ImageContent`](../imagecontent) بوحدات البكسل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | يتخلص من النسخة الحالية. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | يجد جميع الصور في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | يجد الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | يجد جميع العلامات المائية الممكنة في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم إجراء البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### ملاحظات

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### انظر أيضاً

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
