---
title: "Search"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يبحث عن جميع العلامات المائية الممكنة في المستند."
type: docs
weight: 110
url: /ar/net/groupdocs.watermark/watermarker/search/
---
## Search() {#search}

يبحث عن جميع العلامات المائية الممكنة في المستند.

```csharp
public PossibleWatermarkCollection Search()
```

### قيمة الإرجاع

مجموعة العلامات المائية الممكنة.

### ملاحظات

يتم إجراء البحث في الكائنات المحددة في [`SearchableObjects`](../searchableobjects).

تعرف على المزيد حول البحث عن العلامات المائية [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### أمثلة

احسب عدد العلامات المائية الممكنة في مستند من أي نوع مدعوم.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    PossibleWatermarkCollection watermarks = watermarker.Search();
    Console.WrileLine(watermarks.Count);
}
```

### انظر أيضاً

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Search(SearchCriteria) {#search_1}

يبحث عن العلامات المائية الممكنة وفقًا لمعايير البحث المحددة.

```csharp
public PossibleWatermarkCollection Search(SearchCriteria searchCriteria)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| searchCriteria | SearchCriteria | معايير البحث للاستخدام. |

### قيمة الإرجاع

مجموعة العلامات المائية الممكنة.

### ملاحظات

يتم إجراء البحث في الكائنات المحددة في [`SearchableObjects`](../searchableobjects).

تعرف على المزيد حول البحث عن العلامات المائية [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### أمثلة

ابحث وأزل جميع العلامات المائية الممكنة التي تحتوي على نص أو صورة معينة من مستند من أي نوع مدعوم.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarks.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### انظر أيضاً

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [SearchCriteria](../../../groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
