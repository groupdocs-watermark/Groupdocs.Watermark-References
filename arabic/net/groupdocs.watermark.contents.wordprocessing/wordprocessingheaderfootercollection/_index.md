---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل مجموعة من الرؤوس والتذييلات في مستند Word."
type: docs
weight: 1370
url: /ar/net/groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/
---
## WordProcessingHeaderFooterCollection class

يمثل مجموعة من الرؤوس والتذييلات في مستند Word.

```csharp
public class WordProcessingHeaderFooterCollection : ReadOnlyListBase<WordProcessingHeaderFooter>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | يحصل على عدد العناصر الموجودة في المجموعة. |
| virtual [IsReadOnly](../../groupdocs.watermark.common/readonlylistbase-1/isreadonly) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | يحصل على العنصر في الفهرس المحدد داخل المجموعة. |
| [Item](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/item) { get; } | يحصل على الرأس أو التذييل من النوع المحدد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(WordProcessingHeaderFooter) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(WordProcessingHeaderFooter) |  |
| [LinkToPrevious](../../groupdocs.watermark.contents.wordprocessing/wordprocessingheaderfootercollection/linktoprevious)(bool) | يربط أو يفك ربط جميع رؤوس وتذييلات الأقسام بالرؤوس والتذييلات المقابلة في القسم السابق. |

### ملاحظات

تحتوي هذه المجموعة على عناصر من النوع [`WordProcessingHeaderFooter`](../wordprocessingheaderfooter).

### انظر أيضاً

* class [ReadOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/readonlylistbase-1)
* class [WordProcessingHeaderFooter](../wordprocessingheaderfooter)
* namespace [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
