---
title: "VectorSearchCriteria"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل معايير تسمح بالترشيح حسب لون العلامة المائية."
type: docs
weight: 2760
url: /ar/net/groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/
---
## VectorSearchCriteria class

يمثل معايير تسمح بالترشيح حسب لون العلامة المائية.

```csharp
public class VectorSearchCriteria : SearchCriteria
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [VectorSearchCriteria](vectorsearchcriteria)() | ينشئ مثيلًا جديدًا من الفئة [`VectorSearchCriteria`](../vectorsearchcriteria). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [VectorColorRange](../../groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/vectorcolorrange) { get; set; } | يحصل أو يعيّن نطاق الألوان المستخدمة لتصفية العلامات المائية المتجهية حسب لون المقدمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | يجمع هذا [`SearchCriteria`](../searchcriteria) مع معايير أخرى باستخدام عامل AND المنطقي. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | ينفي هذا [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | يجمع هذا [`SearchCriteria`](../searchcriteria) مع معايير أخرى باستخدام عامل OR المنطقي. |

### ملاحظات

**Learn more:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### أمثلة

ابحث وأزل العلامة المائية باستخدام معايير البحث.

```csharp
using (Watermarker watermarker = new Watermarker(@"C:\test.pdf"))
{
    VectorSearchCriteria searchCriteria = new VectorSearchCriteria();
    Color watermarkColor = ColorTranslator.FromHtml("#a9aaae");
    GroupDocs.Watermark.Watermarks.Color fromSystemColor = GroupDocs.Watermark.Watermarks.Color.FromArgb(watermarkColor.A, watermarkColor.R, watermarkColor.G, watermarkColor.B);
    ColorRange criteriaVectorColorRange = new ColorRange(fromSystemColor)
    {
       MinBrightness = 0.1f,
       MaxBrightness = 0.7f
    };
    searchCriteria.VectorColorRange = criteriaVectorColorRange;
    PossibleWatermarkCollection possibleWatermarkCollection = watermarker.Search(searchCriteria);
    possibleWatermarkCollection.Clear();
    watermarker.Save(@"C:\modified_test.pdf");
}
```

### انظر أيضاً

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
