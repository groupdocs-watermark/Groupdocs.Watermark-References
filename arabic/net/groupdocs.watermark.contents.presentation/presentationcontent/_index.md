---
title: "PresentationContent"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل مستند PowerPoint يمكن وضع علامة مائية فيه."
type: docs
weight: 900
url: /ar/net/groupdocs.watermark.contents.presentation/presentationcontent/
---
## PresentationContent class

يمثل مستند PowerPoint يمكن وضع علامة مائية فيه.

```csharp
public class PresentationContent : Content
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [LayoutSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/layoutslides) { get; } | يحصل على مجموعة جميع شرائح التخطيط لهذا [`PresentationContent`](../presentationcontent). |
| [MasterHandoutSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masterhandoutslide) { get; } | يحصل على شريحة النسخة الرئيسية لهذا [`PresentationContent`](../presentationcontent). |
| [MasterNotesSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masternotesslide) { get; } | يحصل على الشريحة الرئيسية لجميع شرائح الملاحظات لهذا [`PresentationContent`](../presentationcontent). |
| [MasterSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/masterslides) { get; } | يحصل على مجموعة جميع الشرائح الرئيسية لهذا [`PresentationContent`](../presentationcontent). |
| [NotesSlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslideheight) { get; } | يحصل على ارتفاع شريحة الملاحظات بالنقاط. |
| [NotesSlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslidewidth) { get; } | يحصل على عرض شريحة الملاحظات بالنقاط. |
| [SlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/slideheight) { get; } | يحصل على ارتفاع الشريحة بالنقاط. |
| [Slides](../../groupdocs.watermark.contents.presentation/presentationcontent/slides) { get; } | يحصل على مجموعة جميع الشرائح لهذا [`PresentationContent`](../presentationcontent). |
| [SlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/slidewidth) { get; } | يحصل على عرض الشريحة بالنقاط. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/decrypt)() | يفك تشفير المستند. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | يتخلص من النسخة الحالية. |
| [Encrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/encrypt)(string) | يقوم بتشفير المستند. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | يجد جميع الصور في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | يجد الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | يجد جميع العلامات المائية الممكنة في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم إجراء البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### ملاحظات

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds)

### أمثلة

تحميل وحفظ مستند PowerPoint من أي نوع مدعوم.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.ppt", loadOptions))
{
    // استخدم طريقة Add لإضافة علامة مائية إلى شريحة معينة أو جميع الشرائح.

    // احفظ التغييرات.
    watermarker.Save(@"D:\output.ppt");
}
```

### انظر أيضاً

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
