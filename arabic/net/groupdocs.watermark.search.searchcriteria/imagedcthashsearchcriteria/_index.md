---
title: "ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل معيار بحث للعثور على الصور في مستند."
type: docs
weight: 2630
url: /ar/net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/
---
## ImageDctHashSearchCriteria class

يمثل معيار بحث للعثور على الصور في مستند.

```csharp
public class ImageDctHashSearchCriteria : ImageSearchCriteria
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor)(Stream) | ينشئ مثيلاً جديدًا لفئة [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) باستخدام تدفق محدد. |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor_1)(string) | ينشئ مثيلاً جديدًا لفئة [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) باستخدام مسار ملف محدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | يحصل أو يضبط الحد الأقصى المسموح به للاختلاف بين الصور. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | يحصل أو يعيّن قائمة أرقام الصفحات المحددة |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | يجمع هذا [`SearchCriteria`](../searchcriteria) مع معايير أخرى باستخدام عامل AND المنطقي. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | ينفي هذا [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | يجمع هذا [`SearchCriteria`](../searchcriteria) مع معايير أخرى باستخدام عامل OR المنطقي. |

### ملاحظات

يستخدم معيار البحث هذا تجزئة الصورة الإدراكية المعتمدة على DCT لحساب تشابه الصور. **اعرف المزيد**:

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### أمثلة

ابحث عن الصور في الملفات المرفقة (pdf).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    PdfSearchableObjects = PdfSearchableObjects.All
};
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions, settings))
{
    // حدد صورة عينة للمقارنة مع صور المستند.
    ImageSearchCriteria criteria = new ImageDctHashSearchCriteria(@"D:\sample.png");
    // ابحث عن صور مشابهة
    PossibleWatermarkCollection possibleWatermarks = watermarker.Search(criteria);
    // إزالة أو تعديل العلامات المائية للصور المكتشفة
    // ...
}
```

### انظر أيضاً

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
