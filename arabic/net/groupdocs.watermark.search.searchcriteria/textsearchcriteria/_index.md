---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل معايير تسمح بالترشيح حسب نص العلامة المائية."
type: docs
weight: 2750
url: /ar/net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/
---
## TextSearchCriteria class

يمثل معايير تسمح بالترشيح حسب نص العلامة المائية.

```csharp
public class TextSearchCriteria : PageSearchCriteria
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextSearchCriteria](textsearchcriteria#constructor_2)(Regex) | تهيئة نسخة جديدة من الفئة [`TextSearchCriteria`](../textsearchcriteria) باستخدام تعبير نمطي محدد. |
| [TextSearchCriteria](textsearchcriteria#constructor)(string) | تهيئة نسخة جديدة من الفئة [`TextSearchCriteria`](../textsearchcriteria) باستخدام سلسلة بحث. |
| [TextSearchCriteria](textsearchcriteria#constructor_1)(string, bool) | تهيئة نسخة جديدة من الفئة [`TextSearchCriteria`](../textsearchcriteria) باستخدام سلسلة بحث وعلامة للمقارنة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | يحصل أو يعيّن قائمة أرقام الصفحات المحددة |
| [Pattern](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/pattern) { get; } | يحصل على نمط البحث. |
| [SkipUnreadableCharacters](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/skipunreadablecharacters) { get; set; } | يحصل أو يعيّن قيمة تشير إلى أنه سيتم تخطي الأحرف غير القابلة للقراءة أثناء مقارنة السلاسل. |

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

* class [PageSearchCriteria](../pagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
