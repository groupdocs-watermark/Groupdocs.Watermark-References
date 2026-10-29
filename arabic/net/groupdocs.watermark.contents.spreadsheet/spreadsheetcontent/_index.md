---
title: "SpreadsheetContent"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل مستند Excel يمكن وضع علامة مائية فيه."
type: docs
weight: 1170
url: /ar/net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
---
## SpreadsheetContent class

يمثل مستند Excel يمكن وضع علامة مائية فيه.

```csharp
public class SpreadsheetContent : Content
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Worksheets](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets) { get; } | يحصل على مجموعة جميع أوراق العمل لهذا [`SpreadsheetContent`](../spreadsheetcontent). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt)() | يفك تشفير المستند. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | يتخلص من النسخة الحالية. |
| [Encrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt)(string) | يشفّر المحتوى. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | يجد جميع الصور في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | يجد الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | يجد جميع العلامات المائية الممكنة في المحتوى. يتم البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم إجراء البحث في الكائنات المحددة في [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### ملاحظات

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)
* [Shapes in spreadsheet document](https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document)
* [Working with spreadsheet document attachments](https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments)
* [Working with worksheet backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds)
* [Working with worksheet headers and footers](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers)

### أمثلة

حمّل واحفظ مستند Excel من أي نوع مدعوم.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.xls", loadOptions))
{
    // استخدم طريقة Add لإضافة علامة مائية إلى ورقة عمل معينة أو جميع أوراق العمل.

    // احفظ التغييرات.
    watermarker.Save(@"D:\output.xls");
}
```

### انظر أيضاً

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
