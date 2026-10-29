---
title: "PdfPage"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل صفحة مستند pdf."
type: docs
weight: 730
url: /ar/net/groupdocs.watermark.contents.pdf/pdfpage/
---
## PdfPage class

يمثل صفحة مستند pdf.

```csharp
public class PdfPage : ContentPart
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Annotations](../../groupdocs.watermark.contents.pdf/pdfpage/annotations) { get; } | يحصل على مجموعة جميع التعليقات التوضيحية لهذه [`PdfPage`](../pdfpage). |
| [Artifacts](../../groupdocs.watermark.contents.pdf/pdfpage/artifacts) { get; } | يحصل على مجموعة جميع العناصر الأثرية لهذه [`PdfPage`](../pdfpage). |
| [Height](../../groupdocs.watermark.contents.pdf/pdfpage/height) { get; } | يحصل على ارتفاع هذه [`PdfPage`](../pdfpage) بالنقاط. |
| [Width](../../groupdocs.watermark.contents.pdf/pdfpage/width) { get; } | يحصل على عرض هذه [`PdfPage`](../pdfpage) بالنقاط. |
| [XObjects](../../groupdocs.watermark.contents.pdf/pdfpage/xobjects) { get; } | يحصل على مجموعة جميع XObjects لهذه [`PdfPage`](../pdfpage). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | يجد جميع الصور في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | يجد الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| virtual [Rasterize](../../groupdocs.watermark.contents.pdf/pdfpage/rasterize)(int, int, PdfImageConversionFormat) | يحوّل محتوى الصفحة إلى صورة. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | يجد جميع العلامات المائية الممكنة في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم إجراء البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### انظر أيضاً

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
