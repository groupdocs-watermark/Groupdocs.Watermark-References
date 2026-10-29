---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل معيار بحث للعثور على الصور في محتوى."
type: docs
weight: 2620
url: /ar/net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/
---
## ImageColorHistogramSearchCriteria class

يمثل معيار بحث للعثور على الصور في محتوى.

```csharp
public class ImageColorHistogramSearchCriteria : ImageSearchCriteria
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor)(Stream) | يقوم بإنشاء نسخة جديدة من الفئة [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) باستخدام تدفق محدد. |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor_1)(string) | يقوم بإنشاء نسخة جديدة من الفئة [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) باستخدام مسار ملف محدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BinsCount](../../groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/binscount) { get; set; } | يحصل أو يضبط عدد الصناديق التي ستُستخدم لإنشاء مخططات الألوان. |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | يحصل أو يضبط الحد الأقصى المسموح به للاختلاف بين الصور. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | يحصل أو يعيّن قائمة أرقام الصفحات المحددة |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | يجمع هذا [`SearchCriteria`](../searchcriteria) مع معايير أخرى باستخدام عامل AND المنطقي. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | ينفي هذا [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | يجمع هذا [`SearchCriteria`](../searchcriteria) مع معايير أخرى باستخدام عامل OR المنطقي. |

### ملاحظات

تستخدم معايير البحث هذه مخططات ألوان الصور لحساب تشابه الصور.

### انظر أيضاً

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
