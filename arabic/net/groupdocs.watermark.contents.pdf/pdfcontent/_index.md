---
title: "PdfContent"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل مستند pdf يمكن وضع علامة مائية فيه."
type: docs
weight: 660
url: /ar/net/groupdocs.watermark.contents.pdf/pdfcontent/
---
## PdfContent class

يمثل مستند pdf يمكن وضع علامة مائية فيه.

```csharp
public class PdfContent : Content
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.pdf/pdfcontent/attachments) { get; } | يحصل على مجموعة جميع المرفقات لهذا [`PdfContent`](../pdfcontent). |
| [PageMarginType](../../groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype) { get; set; } | يحصل على أو يضبط هوامش صفحة pdf التي ستُستخدم أثناء إضافة العلامة المائية. |
| [Pages](../../groupdocs.watermark.contents.pdf/pdfcontent/pages) { get; } | يحصل على مجموعة جميع الصفحات لهذا [`PdfContent`](../pdfcontent). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/decrypt)() | يفك تشفير المحتوى. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | يتخلص من النسخة الحالية. |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt)(string) | يشفّر المستند باستخدام نفس كلمة المرور ككلمة مرور المستخدم وكلمة مرور المالك. |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt_1)(string, string, PdfPermissions, PdfCryptoAlgorithm) | يشفّر المحتوى. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | يجد جميع الصور في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | يجد الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Rasterize](../../groupdocs.watermark.contents.pdf/pdfcontent/rasterize)(int, int, PdfImageConversionFormat) | يحوّل جميع صفحات المحتوى إلى صور. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | يجد جميع العلامات المائية الممكنة في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم إجراء البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### ملاحظات

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
* [Existing objects in PDF document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
* [Rasterize document or page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
* [Watermarks in PDF document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

### انظر أيضاً

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
