---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل مجموعة من الكائنات المضمّنة في رسالة بريد إلكتروني."
type: docs
weight: 380
url: /ar/net/groupdocs.watermark.contents.email/emailembeddedobjectcollection/
---
## EmailEmbeddedObjectCollection class

يمثل مجموعة من الكائنات المضمّنة في رسالة بريد إلكتروني.

```csharp
public class EmailEmbeddedObjectCollection : RemoveOnlyListBase<EmailEmbeddedObject>
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
| [Add](../../groupdocs.watermark.contents.email/emailembeddedobjectcollection/add)(byte[], string) | يضيف موردًا مدمجًا إلى [`EmailContent`](../emailcontent). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(EmailEmbeddedObject) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(EmailEmbeddedObject) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(EmailEmbeddedObject) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### ملاحظات

تحتوي هذه المجموعة على عناصر من نوع [`EmailEmbeddedObject`](../emailembeddedobject).

### انظر أيضاً

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [EmailEmbeddedObject](../emailembeddedobject)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
