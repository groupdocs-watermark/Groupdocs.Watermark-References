---
title: "RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل معيارًا يسمح بالتصفية حسب زاوية دوران العلامة المائية."
type: docs
weight: 2710
url: /ar/net/groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/
---
## RotateAngleSearchCriteria class

يمثل معيارًا يسمح بالتصفية حسب زاوية دوران العلامة المائية.

```csharp
public class RotateAngleSearchCriteria : SearchCriteria
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [RotateAngleSearchCriteria](rotateanglesearchcriteria)(double, double) | ينشئ مثيلاً جديدًا لفئة [`RotateAngleSearchCriteria`](../rotateanglesearchcriteria) بزاوية بدء وزاوية انتهاء. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [MaximumAngle](../../groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/maximumangle) { get; } | يحصل على زاوية الانتهاء بالدرجات. |
| [MinimumAngle](../../groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/minimumangle) { get; } | يحصل على زاوية البدء بالدرجات. |

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

ابحث وأزل العلامات المائية باستخدام معيار البحث.

```csharp
using (Watermarker watermarker = new Watermarker(@"C:\test.some_ext"))
{
    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
    TextSearchCriteria textCriteria = new TextSearchCriteria(new Regex("^Test watermark$"));
    PossibleWatermarkCollection watermarks = watermarker.Search(textCriteria.And(widthRange.Or(rotateAngle)));
    watermarks.Clear();
    watermarker.Save();
}
```

### انظر أيضاً

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
