---
title: "AttachmentWatermarkableImage"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل صورة مرفقة داخل محتوى من أي نوع مدعوم."
type: docs
weight: 20
url: /ar/net/groupdocs.watermark.common/attachmentwatermarkableimage/
---
## AttachmentWatermarkableImage class

يمثل صورة مرفقة داخل محتوى من أي نوع مدعوم.

```csharp
public class AttachmentWatermarkableImage : WatermarkableImage
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | يحصل على ارتفاع هذه [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) بالبيكسل. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | يحصل على عرض هذه [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) بالبيكسل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | يضيف علامة مائية إلى هذه [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage). تفترض هذه الطريقة أن إزاحة العلامة المائية وحجمها يُقاسان بالبيكسل (إذا تم تعيينهما). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | يجد جميع الصور في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | يجد الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | يحصل على الصورة كمصفوفة بايت. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | يجد جميع العلامات المائية الممكنة في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم إجراء البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### انظر أيضاً

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
