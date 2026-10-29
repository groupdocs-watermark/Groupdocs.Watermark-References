---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل معايير تسمح بالترشيح حسب حجم العلامة المائية."
type: docs
weight: 2730
url: /ar/net/groupdocs.watermark.search.searchcriteria/sizesearchcriteria/
---
## SizeSearchCriteria class

يمثل معايير تسمح بالترشيح حسب حجم العلامة المائية.

```csharp
public class SizeSearchCriteria : SearchCriteria
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SizeSearchCriteria](sizesearchcriteria)(Dimension, double, double) | يقوم بإنشاء نسخة جديدة من الفئة [`SizeSearchCriteria`](../sizesearchcriteria) باستخدام بُعد محدد، قيمة بداية وقيمة نهاية. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Dimension](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/dimension) { get; } | يحصل على بُعد العلامة المائية التي يتم البحث عنها. |
| [Maximum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/maximum) { get; } | يحصل على قيمة النهاية. |
| [Minimum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/minimum) { get; } | يحصل على قيمة البداية. |

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
