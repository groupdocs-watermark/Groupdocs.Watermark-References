---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل معيار بحث للعثور على الصور في محتوى."
type: docs
weight: 2650
url: /ar/net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/
---
## ImageThumbnailSearchCriteria class

يمثل معيار بحث للعثور على الصور في محتوى.

```csharp
public class ImageThumbnailSearchCriteria : ImageSearchCriteria
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor)(Stream) | تهيئة نسخة جديدة من الفئة [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) باستخدام تدفق محدد. |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor_1)(string) | تهيئة نسخة جديدة من الفئة [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) باستخدام مسار ملف محدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | يحصل أو يضبط الحد الأقصى المسموح به للاختلاف بين الصور. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | يحصل أو يعيّن قائمة أرقام الصفحات المحددة |
| [ThumbnailSize](../../groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/thumbnailsize) { get; set; } | يحصل أو يعيّن حجم الصورة المصغرة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | يجمع هذا [`SearchCriteria`](../searchcriteria) مع معايير أخرى باستخدام عامل AND المنطقي. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | ينفي هذا [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | يجمع هذا [`SearchCriteria`](../searchcriteria) مع معايير أخرى باستخدام عامل OR المنطقي. |

### ملاحظات

يستخدم هذا المعيار البحثي الصورة المصغرة الثنائية لحساب تشابه الصور.

### انظر أيضاً

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
