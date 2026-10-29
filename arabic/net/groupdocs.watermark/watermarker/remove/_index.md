---
title: "Remove"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يزيل العلامة المائية من المستند."
type: docs
weight: 90
url: /ar/net/groupdocs.watermark/watermarker/remove/
---
## Remove(PossibleWatermark) {#remove}

يزيل العلامة المائية من المستند.

```csharp
public void Remove(PossibleWatermark possibleWatermark)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| possibleWatermark | PossibleWatermark | العلامة المائية المراد إزالتها. |

### ملاحظات

تعرف على المزيد حول إزالة العلامات المائية: [إزالة العلامات المائية المكتشفة](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### أمثلة

ابحث وأزل أول علامة مائية محتملة تحتوي على نص أو صورة معينة من مستند من أي نوع مدعوم.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    if (watermarks.Count > 0)
    {
        watermarker.Remove(watermarks[0]);
    }

    watermarker.Save(@"D:\output.doc");
}
```

### انظر أيضاً

* class [PossibleWatermark](../../../groupdocs.watermark.search/possiblewatermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Remove(PossibleWatermarkCollection) {#remove_1}

يزيل جميع العلامات المائية في المجموعة من المستند.

```csharp
public void Remove(PossibleWatermarkCollection possibleWatermarks)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| possibleWatermarks | PossibleWatermarkCollection | مجموعة العلامات المائية المراد إزالتها. |

### ملاحظات

تعرف على المزيد حول إزالة العلامات المائية [إزالة العلامات المائية المكتشفة](https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks).

### أمثلة

ابحث وأزل جميع العلامات المائية الممكنة التي تحتوي على نص أو صورة معينة من مستند من أي نوع مدعوم.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarker.Remove(watermarks);
    watermarker.Save(@"D:\output.doc");
}
```

### انظر أيضاً

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
