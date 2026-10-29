---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل مجموعة من المرفقات في مستند Excel."
type: docs
weight: 1110
url: /ar/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/
---
## SpreadsheetAttachmentCollection class

يمثل مجموعة من المرفقات في مستند Excel.

```csharp
public class SpreadsheetAttachmentCollection : RemoveOnlyListBase<SpreadsheetAttachment>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | يحصل على عدد العناصر الموجودة في المجموعة. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | يحصل على العنصر في الفهرس المحدد داخل المجموعة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddAttachment](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment)(byte[], string, byte[], double, double, double, double) | يضيف مرفقًا إلى [`SpreadsheetWorksheet`](../spreadsheetworksheet). |
| [AddLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addlink)(string, byte[], double, double, double, double) | يضيف مرفقًا عبر رابط (لن يحتوي المستند على محتوى الملف المرفق). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(SpreadsheetAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(SpreadsheetAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(SpreadsheetAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### ملاحظات

تحتوي هذه المجموعة على عناصر من نوع [`SpreadsheetAttachment`](../spreadsheetattachment).

### انظر أيضاً

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [SpreadsheetAttachment](../spreadsheetattachment)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
